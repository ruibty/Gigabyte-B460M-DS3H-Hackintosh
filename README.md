核显OpenCore方案。

电脑是公司闲置的，网上找了些EFI拼起来，修复了升级 `大乌苏`之后出现的USB无法使用的问题。修复了可能出现的紫屏。

目前个人使用没问题。

2021/10/20：这个主板已经不是我的了，这个项目也不会再更新了。

## 注意

- 务必更新 `Serial`/`SystemSerialNumber`、`Board Serial`/`MLB`、`SmUUID`/`SystemUUID`
- 仅使用 `EFI`文件夹及其子文件即可，其他无用。
- 本项目仅供参考

## 硬件

| header 1         | header 2                                 |
| ---------------- | ---------------------------------------- |
| CPU              | Intel(R) Core(TM) i5-10400 CPU @ 2.90GHz |
| OS               | macOS Big Sur 版本11.4（版号20F71）      |
| 显卡             | Intel CometLake-S GT2 [UHD Graphics 630] |
| OpenCore Version | 0.6.1                                    |

![about](https://ruibty.github.io/Gigabyte-B460M-DS3H-Hackintosh/docs/about.jpg)
