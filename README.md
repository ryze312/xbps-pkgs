# xbps-pkgs
Personal repository of packages for [Void Linux](https://voidlinux.org).

## Configuration
You can configure this repository by adding a xbps configuration file, for example at `/etc/xbps.d/xbps-pkgs.conf`:
```
repository=https://raw.githubusercontent.com/ryze312/xbps-pkgs/repository-PLATFORM
```
Replace `PLATFORM` accordingly for your Void installation, e.g `x86_64-glibc`.

Make sure to refresh repository data:
```
sudo xbps-install -S
```

## Available platforms
The packages are built automatically using [workflow](.github/workflows/build.yml) for the following platforms:
- x86_64-glibc
- i686-glibc

## Special thanks
- [xbps-extra]([https://github.com/VanillaDaFur/xbps-extra]) for providing an example workflow for building packages.

## Contributing
Feel free to open an issue or submit a PR if you have any problems or want to request a new package.
