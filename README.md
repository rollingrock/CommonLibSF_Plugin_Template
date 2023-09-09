# Project Plugin Template for CommonLibSF
Starter Project Template for use with CommonLibSF for Starfield SFSE Plugin Development

## Build Dependencies

- [CMake 3.26+](https://cmake.org/)
  - Add this to your PATH
- [vcpkg](https://github.com/microsoft/vcpkg)
  - Add the environment variable `VCPKG_ROOT` with the value as the path to the folder containing vcpkg
- [Visual Studio 2022](https://visualstudio.microsoft.com/) with "Desktop development with C++"
  - clang-cl toolset and build support if using `clang-cl` configuration
- [PowerShell](https://github.com/PowerShell/PowerShell/releases)

#### vcpkg

[See how to use CommonLibSF with vcpkg in your project.](https://github.com/Starfield-Reverse-Engineering/Starfield-RE-vcpkg)

## git submodule

CommonLibSF is linked as a submodule in the extern directory.    YOu can configure this to your own fork but make sure to update Common lib with this after cd into your project directory in git bash or your git tool of choice

```bash
git submodule update
```

## CommonLibSF
https://github.com/Starfield-Reverse-Engineering/CommonLibSF


