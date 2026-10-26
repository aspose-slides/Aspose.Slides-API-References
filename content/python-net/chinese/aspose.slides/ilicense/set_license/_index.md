---
title: set_license method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ilicense/set_license/
weight: 30
---
## set_license(self, license_name) {#str}
为组件授权。


```python
def set_license(self, license_name):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| license_name | **str** | 可以是完整或简短的文件名，或嵌入资源的名称。<br/><br/>使用空字符串切换到评估模式。 |

### 备注

尝试在以下位置查找许可证：


1. 显式路径。

2. 组件程序集的文件夹。

3. 客户端调用程序集的文件夹。

4. 入口程序集的文件夹。

5. 客户端调用程序集中的嵌入资源。

**注意：** 在 .NET Compact Framework 上，仅尝试在以下位置查找许可证：


1. 显式路径。

2. 客户端调用程序集中的嵌入资源。


## set_license(self, stream) {#iorawiobase}
为组件授权。


```python
def set_license(self, stream):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 包含许可证的流。 |

### 备注

使用此方法从流中加载许可证。



### 另请参见
* 类 [`ILicense`](/slides/python-net/zh/aspose.slides/ilicense)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)