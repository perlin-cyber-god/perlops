# PERLOPS

My own computer: a collection of Hack platform and Nand2Tetris experiments, written
primarily in Jack, alongside a Vivado project and screen recordings.

## Projects

| Folder | What it contains |
| --- | --- |
| `explorer/` | A Jack Mandelbrot explorer for Hack, with fixed-point arithmetic, progressive rendering, and keyboard-controlled navigation. |
| `perlos/` | Jack graphics and animation code, including a falcon drawing, glyph helpers, trigonometry, and a show/demo module. |
| `project_1/` | A Vivado project with project metadata and generated XSim simulation/cache files. Some HDL source paths referenced by the project point outside this repository. |
| `raycaster/` | A Jack entry-point animation that runs a repeating PERLOPS falcon intro. |
| `raytracing/` | A Jack entry point that creates and runs a `Game` instance. |
| `some_cool_shit/` | Jack graphics helpers and a repeating brand-reveal animation. |
| `tetris/` | Jack game and graphics experiments, including a `Game` class and a low-resolution sphere ray-tracing demo. |

## Other files

- `project_showcase.zip` is an archive of selected Jack showcase projects.
- The `Screencast From ... .webm` files are screen recordings.

The Jack projects are intended for the Hack computer platform and require a
compatible Nand2Tetris toolchain to build and run.
