# 校园智障英语
[![Python package](https://github.com/wxh06/xyzzyy-cli/workflows/Python%20package/badge.svg)](https://github.com/wxh06/xyzzyy-cli/actions?query=workflow%3A%22Python+package%22)
[![Build Status](https://travis-ci.com/wxh06/xyzzyy-cli.svg)](https://travis-ci.com/wxh06/xyzzyy-cli)

This is a Python script for finishing the homework automatically on an educational platform in China. If you see this repository by mistake, I'm sorry that it may not be useful to you.

用于完成[校园智慧英语平台](http://pc.pjjy.com/)作业的自动化脚本

目前仅适配了上海民办南模中学的[`http://114.118.97.15`](http://114.118.97.15/page/pc/?db=site_20180305000000)，其它学校大同小异，欢迎各校大佬 [pr](https://github.com/wangxinhe2006/xyzzyy-cli/pulls)。如遇问题，请[创建议题](https://github.com/wangxinhe2006/xyzzyy-cli/issues/new)（[issue](https://github.com/wangxinhe2006/xyzzyy-cli/issues)）以便修复。

## Requirements
Python 3.6 or later: <https://www.python.org/downloads/>

## Usage
#### 下载
Download ZIP:
<https://github.com/wangxinhe2006/xyzzyy-cli/archive/master.zip>

[Clone](https://git-scm.com/docs/git-clone) via [Git](https://git-scm.com/):
```sh
git clone https://github.com/wangxinhe2006/xyzzyy-cli.git
git clone git@github.com:wangxinhe2006/xyzzyy-cli.git
```
#### 运行
1. 运行位于[`xyzzyy/__init__.py`](xyzzyy/__init__.py)处的 Python 脚本。
2. 输入站点及数据库。对于上海民办南模中学，留空以使用默认值即可。
3. 输入姓名。
4. 若支持，则使用键盘上的左右箭头（<kbd>←</kbd><kbd>→</kbd>）选择需要进行的操作；否则，请完整键入所给选项之一。按回车键（<kbd>return</kbd> or <kbd>enter</kbd>）开始。部分操作开始之前，将会征询用户意见。

### Legacy
1. 在浏览器中登录校园智慧英语后，复制名为`pj`的 Cookie
2. 运行[`legacy`](legacy)目录中相应的 Python 脚本，按提示输入站点地址及名为`pj`的 Cookie 等信息

## [License](LICENSE)
Copyright &copy; 2020 [汪心禾](https://github.com/wangxinhe2006), Licensed under [the **MIT License**](https://choosealicense.com/licenses/mit/)

根据[**麻省理工学院许可协议**](https://opensource.org/licenses/MIT)进行授权，在您使用、复制或再次分发时理当保留许可协议和版权声明的副本
