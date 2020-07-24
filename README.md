# Zig OpenGL Playground

## Dependencies

- GLAD (vendored)
- STB (vendored)
- GLFW (byo)

All dependencies except for GLFW are vendored under `deps/`. For GLFW, install using your OS package
manager, or if using windows, install using something like `vcpkg` and edit the paths in `build.zig`.

## Running

Check `build.zig` for the full list of implemented stages, to run the relevant stage, just run its
zig build command, for example:

```bash
zig build hello_triangle    # Renders a colorful triangle
zig build camera            # Renders a scene with many boxes and a camera
zig build multiple_lights   # Renders the same scene but with diffuse/specular maps and multiple lights
```

## Note

The playground start as a folk of [Learn OpenGL zig port by Charles Shenton](https://github.com/cshenton/learnopengl)
