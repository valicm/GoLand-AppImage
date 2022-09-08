<p align="center"><img width="128px" height="128px" src="https://resources.jetbrains.com/storage/products/company/brand/logos/GoLand_icon.png" alt="GoLand logo."></p>
<h2 align="center">GoLand AppImage</h2>
<h3 align="center">Unofficial / Community provided GoLand AppImage</h3>

[![GoLand AppImage release](https://github.com/valicm/GoLand-AppImage/actions/workflows/release.yml/badge.svg?branch=main)](https://github.com/valicm/GoLand-AppImage/actions/workflows/release.yml)

## Get Started

#### [Download the latest release](https://github.com/valicm/GoLand-AppImage/releases/latest)
- stable release only
- supports update of the AppImage

### Executing
#### File Manager
Double-click the `*.AppImage` file and you are done!

> In normal cases, the above method should work, but in some cases you 
> need mark file as executable. You can do this using File manager -> right click > Properties > Allow Execution,
> or by terminal issuing command `chmod +x GoLand-*.AppImage`

#### AppImageLauncher
Use AppImageLauncher for better desktop integration ==> [download AppImageLauncher](https://github.com/TheAssassin/AppImageLauncher)

#### Terminal
```bash
chmod +x GoLand-*.AppImage
./GoLand-*.AppImage
```

#### Build
The AppImage is built from .tar.gz GoLand package by GitHub Continuous Integration 
with [appimage-bash Github Action](https://github.com/marketplace/actions/appimage-bash).

____________________________________________________________________________________________________________________________________
_GoLand and the GoLand logo are registered trademarks of JetBrains s.r.o._
