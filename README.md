# Project ReBlack — BLACK PC Port

Project ReBlack is the foundation for a native PC port of *BLACK*. The reverse-engineering and source reconstruction work for the original Xbox is documented separately in [ReBLACK-XBOX](https://github.com/soldieg/ReBLACK-XBOX).

This repository is newly initialized. It does not yet contain a PC port implementation, executable, or build.

## Project direction

The Xbox reconstruction is a technical reference, not a ready-made PC port. The PC project will need to define its target operating systems and toolchain, replace Xbox-specific APIs and runtime assumptions, and validate behavior on the PC target.

## Initial work

- Choose the supported PC platform and build toolchain.
- Map Xbox-specific systems and dependencies that need PC replacements.
- Establish a small buildable foundation before porting game systems.
- Add behavior and regression checks as each system is implemented.

Project planning and code will be AI-assisted under human direction and review.
