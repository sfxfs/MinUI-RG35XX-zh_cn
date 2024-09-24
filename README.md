# MinUI

[Original README](README_ORIG.md)

<img src="github/minui-main.png" width=320 /> <img src="github/minui-menu-gbc.png" width=320 /> 

## 介绍

将大部分菜单翻译为了简体中文（除了模拟器后端的相关选项）

在 RG35XX PLUS 上测试成功，字体为得意黑，在字体较小的情况下效果略差，但是算比较贴合原先字体（以后可能更换更合适的字体）

如果你已经安装了 **MinUI** 则直接拷贝 *Release* 压缩包里面的 *MinUI.zip* 到卡二根目录即可触发升级，没有的话请参照压缩包内的 **README.txt**

## 编译

推荐 Ubuntu 22.04 ，安装好 make, zip, docker，前两个可以直接包管理器安装，docker 请参考网上教程或者官方文档安装，一切准备就绪后进入项目目录然后输入 `sudo make` 命令进行编译，产出的包会在 releases 文件夹内。