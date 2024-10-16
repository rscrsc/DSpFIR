# DSpFIR - Domain-Specific Format Intermediate Representation

*Have you ever felt intimidated by a strange niche format when you have to deal with it?*
*There's no need to read the long long meticulous documentation!*
*After all they are data, and data semantics can be well described.*

This python package provides a toolkit, with which you can:
- Covert data from any format you need, to any format you want
- Understand a new format just by reading its format description here
- Create, download and share user-defined format descriptions

## Overview
![overview](./assets/overview_dark.png#gh-dark-mode-only)
![overview](./assets/overview_light.png#gh-light-mode-only)

- The `<FORMAT>.fd`s should follow a human-readable syntax to describe a data format. *("fd" means "Format Description")*
- The `<DATA>.fir` is an encoded intermediate representation in DSpFIR-defined bytecode. *("fir" means "Format Intermediat Representation")*
- `<FORMAT>.fd`s can be simply from DSpFIR format library or defined by yourself if you want.

## TODO
- Define the universal symbolic description of a data format (sematics of .fd files)
- Define the intermediate representation bytecode format (structure of .fir files)
- Encoder & Decoder
- Add .fd files for some common format to DSpFIR library
