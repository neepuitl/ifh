# 文件帮助器
文件帮助器主要是协助你自动化处理大批量文件，例如文件去重。

目前支持: 

- **文件去重**： 自动移除目录下的重复文件到目标目录。

## 1. 环境
> 编译器 >= `Python3.6`

> 包管理工具 >= `pip3`

## 2. 安装
- 步骤1
    > python3 setup.py install

## 3. 用法
### 3.1. 帮助
> fihe -h

### 3.2. 查看重复文件
> fihe ls --root-dir="<absolute_root_dir>"

**注意**：`root-dir`是你查看重复文件的根目录。

### 3.3. 去除重复文件
> fihe rm --root-dir="<absolute_root_dir>" --target-dir="<absolute_target_dir>"

**注意**：`root-dir`是你将要进行文件去重复的目录，`target-dir`是重复文件将要移动到的目标目录。