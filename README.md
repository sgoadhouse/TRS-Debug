# TRS-Debug

A custom board to allow two Tip-Ring-Sleeve connectors to pass-through
their signals and be able to monitor them.

The Altium Designer v26 (AD26) schematic and layout tool was used to
design the board and the source files here can only be read through
Altium Designer. Most versions of AD should be able to view the
project files. You can also use the [Altium Designer
Viewer](https://www.altium.com/altium-designer-viewer) to view these
files.

## Design Output Files

In addition to the source files, there should be various output files
in PDF, Gerber and other formats. They are located under the folder,
[Project Outputs for TRS-Debug](./Project%20Outputs%20for%20TRS-Debug).

# Before cloning the GIT repository

Make sure that ...

1) The setup is ready for large filesystems on github

```
$ git lfs install
```

1) You have git version 2.13.0 (or later) installed

```
$ git version
git version 2.13.0
```

1) Verify that you have git-lfs version 2.1.1 (or later) installed

```
$ git-lfs version
git-lfs/2.1.1
```

# UVaND-Libraries submodule

The UVaND-Libraries submodule contains a Altium component database,
symbols and footprints library that were used in the design. This is
sourced from gitlab.cern.ch which is likely not accessible to the
majority of github users. However, it is not needed because Altium
copies over the symbol and footprints for any symbol added to the
schematic and embeds these parts within the SchDoc and PcbDoc files
available in this repo. So any git warnings about not being able to
access this submodule can be safely ignored.

# Usage

nothing yet ...


