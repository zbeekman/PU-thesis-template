PU PhD. thesis template
=======================

This is an update to Jeffery Dwoskin's puthesis class and puthesis
template, which itself was adapted from the Princeton University
Mathematics Department's thesis template.

The main contribution of this iteration is to use
[CMake](http://cmake.org) and
[UseLATEX](https://github.com/kmorel/UseLATEX) to build the LaTeX
file(s) which trivializes document compilation, image format
conversion and changing between digital, ProQuest and print
modes. Care was taken to preserve backward compatibility so that a use
provided build-script, makefile or series of commands can be used in
the same way as was originally required, before the CMake build
functionality was added. For more information also consult the
[PU-Template-Instructions](./PU-Template-Instructions.pdf).
