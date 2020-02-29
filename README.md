This repository holds external dependencies needed to build VGMTrans (Qt) on Windows.

While it can be used to build debug builds, it should not be used to set up a development environment.
Both Qt and FluidSynth have to live as dynamic libraries: FluidSynth uses GLib, which can't be built statically on Windows, and static Qt doesn't seem to be well-supported in general (besides producing __extremely large__ binaries)
