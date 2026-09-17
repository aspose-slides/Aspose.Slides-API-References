---
title: Presentation constructor
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/presentation/__init__/
weight: 10
---
## __init__(self) {#}
此构造函数从头创建新的演示文稿。
            已创建的演示文稿包含一个空幻灯片。

```python
def __init__(self):
    ...
```



## __init__(self, load_options) {#loadoptions}
此构造函数从头创建新的演示文稿。
            已创建的演示文稿包含一个空幻灯片。

```python
def __init__(self, load_options):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| load_options | [`LoadOptions`](/slides/python-net/zh/aspose.slides/loadoptions) | 附加加载选项。 |


## __init__(self, stream) {#iorawiobase}
此构造函数是读取现有演示文稿的主要机制。

```python
def __init__(self, stream):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 输入流。 |


## __init__(self, file) {#str}
此构造函数获取源文件路径，  
             演示文稿的内容将被读取。

```python
def __init__(self, file):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file | **str** | 输入文件。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 当输入文件长度为零时抛出 |


## __init__(self, stream, load_options) {#iorawiobase-loadoptions}
此构造函数是读取现有演示文稿的主要机制。

```python
def __init__(self, stream, load_options):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 输入流。 |
| load_options | [`LoadOptions`](/slides/python-net/zh/aspose.slides/loadoptions) | 附加加载选项。 |


## __init__(self, file, load_options) {#str-loadoptions}
此构造函数获取源文件路径，  
            演示文稿的内容将被读取。

```python
def __init__(self, file, load_options):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file | **str** | 输入文件。 |
| load_options | [`LoadOptions`](/slides/python-net/zh/aspose.slides/loadoptions) | 附加加载选项。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 当输入文件长度为零时抛出 |



### 另见
* 类 [`LoadOptions`](/slides/python-net/zh/aspose.slides/loadoptions)
* 类 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)