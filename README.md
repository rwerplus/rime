# RIME

> 当前未在 MacOS 中调试，所以只适配了 Windows 系统

# 皮肤预览（Windows）

> 黑色主题 Lumk_dark
![image](https://github.com/rwerplus/rime/assets/48611415/277c4d6d-32b2-464a-a400-12ab9b892305)

> 亮色主题 Lumk_Light
![image](https://github.com/rwerplus/rime/assets/48611415/af3fa049-e5f4-4906-9f93-785a44a153c9)


使用的字体为[LXGW WenKai](https://github.com/lxgw/LxgwWenKai)

// 使用的字体为悦圆（商用需购买，个人可以免费使用）

# 使用

安装步骤：  
1. 备份原有配置（如有）  
2. 下载仓库压缩包并解压  
3. 打开用户设置  
4. 将本仓库中除了README.md和resources文件夹之外的所有文件复制到用户设置文件夹中  
5. 重新部署鼠须管  

由于主要使用Windows系统，因此在其他平台上可能会遇到一些小问题。
～ 注意 ⚠️：Windows 7 只能使用 0.14.3 版本

# 自定义

## 如何同步

在根目录下添加 installation.yaml 文件，并在其中添加

```yaml
distribution_code_name: Weasel
distribution_name: "小狼毫"
distribution_version: 0.15.0.0
install_time: "Wed Dec  9 15:32:16 2020"
installation_id: "a67da375-4ab1-4331-be02-078713dfce08"
rime_version: 1.8.5
sync_dir: "D:\\Rime\\Win"
update_time: "Wed Sep 13 10:23:33 2023"
```

> 其中 sync_dir 为同步路径，可以使用 webdav 进行同步此文件夹

## 如何修改主题

在 weasel.custom.yaml 文件中修改使用的主题名称，并在 weasel.yaml 中修改主题色，其中大部分都添加了注释，可根据提示修改即可；

```yaml
tips: __include属性为预设主题配置
```
### 鸣谢

* [自然快手](https://github.com/functoreality/rime-flypy-zrmfast), 本项目方案最开始受到此项目启发, 多个功能来源于它
* [雾凇拼音](https://github.com/iDvel/rime-ice), 本项目方案词库由此项目转换而来, 一些功能来源于它
* [汉字部件拆字](https://github.com/mirtlecn/rime-radical-pinyin), 汉字反查方案功能来源于它
* [Rime 输入法双拼加辅助码方案](https://github.com/boomker/rime-fast-xhup),  参考方案
* [Rime](http://rime.im/),  开源输入法框架, 本项目方案来源于它
* 热心网友, 其他开源输入法方案

# 支持的词库

- 部署完成后无法使用或者部署长时间没反应看这里 https://github.com/boomker/rime-fast-xhup/issues/13
- [新增输入法双拼加辅助码方案](https://github.com/boomker/rime-fast-xhup)

  
![Alt text](resources/image-4.png)
![Alt text](resources/image-1.png)
![Alt text](resources/image-2.png)
![Alt text](resources/image-3.png)








