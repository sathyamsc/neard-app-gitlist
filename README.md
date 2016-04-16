This a sub-repo of [Neard project](https://github.com/crazy-max/neard) involving Gitlist app bundles.

## Installation

* Download and install [Neard](https://github.com/crazy-max/neard).
* If you already have installed Neard, stop it.
* Download [a Gitlist bundle](#download).
* Extract archive in `neard\apps\gitlist\`. Directory structure example :

```
[-] neard
 | [-] apps
 |  | [-] gitlist 
 |  |  | [-] gitlist0.4.0
 |  |     | neard.conf
 |  |  | [-] gitlist0.5.0
 |  |     | neard.conf
 ```

* Edit the `neard.conf` file and replace the key `gitlistVersion` with the correct version.
* Edit the `alias/gitlist.conf` file and replace the lines with the correct version. 
* Start Neard.

## Download

![](https://raw.github.com/crazy-max/neard-app-gitlist/master/img/star-20160403.png) : Default bundle on Neard.

|                     | Gitlist release date | Neard release | Download |
| --------------------|:--------------------:|:-------------:|:--------:|
| **Gitlist 0.4.0** ![](https://raw.github.com/crazy-max/neard-app-gitlist/master/img/star-20160403.png) | 2013/06/01 | [r1](https://github.com/crazy-max/neard-app-gitlist/releases/tag/r1) | [neard-gitlist-0.4.0-r1.zip](https://github.com/crazy-max/neard-app-gitlist/releases/download/r1/neard-gitlist-0.4.0-r1.zip) |
| **Gitlist 0.5.0** | 2014/06/30 | [r2](https://github.com/crazy-max/neard-app-gitlist/releases/tag/r2) | [neard-gitlist-0.5.0-r2.zip](https://github.com/crazy-max/neard-app-gitlist/releases/download/r2/neard-gitlist-0.5.0-r2.zip) |

## Sources

* http://gitlist.org/
* https://github.com/klaussilveira/gitlist/releases

## Contribute

If you want to contribute to this bundle and create new bundles, you have to download [neard-dev](https://github.com/crazy-max/neard-dev) in the parent folder of the bundle.
Directory structure example :

```
[-] neard-dev
 | [-] build
 |  |  | build-commons.xml 
[-] neard-app-gitlist
 |  | build.xml
```

To create a new bundle :
* Do not forget to increment the `build.release` in the `build.properties` file.
* If you want you can change the `build.path` (default `C:\neard-build`).
* Open a command prompt in your bundle folder and call the Ant target `release` : `ant release`.
* Upload your release on a file hosting system like [Sendspace](https://www.sendspace.com/).
* Create an [issue on Neard repository](https://github.com/crazy-max/neard/issues) to integrate your release.

## Issues

Issues must be reported on [Neard repository](https://github.com/crazy-max/neard/issues).<br />
Please read [Found a bug?](https://github.com/crazy-max/neard#found-a-bug) section before reporting an issue.
