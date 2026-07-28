# Yi3D Windows Library Bundles

This repository provides prebuilt third-party libraries needed to compile Yi3D under Windows.

## Contents

| Library | Version | Description |
|---------|---------|-------------|
| OpenCASCADE (OCCT) | 7.7 | Open CASCADE Technology — 3D modeling kernel |
| OpenSceneGraph (OSG) | 3.6.5 | 3D rendering engine |
| Qt 5 | 5.15.2 | Cross-platform UI framework |
| Python 3 | 3.10 | Scripting language |
| WYAF | 1.0.0 | WY application framework (wyap, wydb, wyrx, wy core) 

## Usage

1. Download the latest bundle archive from this repository.
2. Extract it into the Yi3D source tree at `<Yi3D-root>/3rdParty/bundles/`:

After extraction the directory will look like:

```
yi3d/
└── 3rdParty/
    └── bundles/
        ├── occt/
        ├── osg/
        ├── python3/
        ├── qt5/
        └── wyaf/
```

3. The Yi3D CMake build system will locate the libraries automatically under `3rdParty/bundles/`.

## Requirements

- Windows 10 or later (64-bit)
- Visual Studio 2019 or later (v142 toolset)
- CMake 3.10+

## Notes

- All binaries are built for the **x64** platform. Both Release and Debug configurations are provided where applicable.

## License

The libraries included in this bundle are distributed under their respective open-source licenses. See each library's documentation for details.
