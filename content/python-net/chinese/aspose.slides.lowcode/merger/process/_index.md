---
title: process method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides.lowcode/merger/process/
weight: 10
---
## process(input_file_names, output_file_name) {#liststr-str}
将多个相同格式的 PowerPoint 演示文稿合并为一个演示文稿文件。

```python
@staticmethod
def process(input_file_names, output_file_name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| input_file_names | **List[str]** | 输入演示文稿文件名的数组。 |
| output_file_name | **str** | 合并后生成的演示文稿文件的输出文件名。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 当输入文件名无效或格式不匹配时抛出。 |

## process(input_file_names, output_stream) {#liststr-iorawiobase}
将多个相同格式的 PowerPoint 演示文稿合并为一个演示文稿文件。

```python
@staticmethod
def process(input_file_names, output_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| input_file_names | **List[str]** | 输入演示文稿文件名的数组。 |
| output_stream | **io.RawIOBase** | 输出流。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 当输入文件名无效或格式不匹配时抛出。 |

## process(input_file_names, output_file_name, options) {#liststr-str-asposeslidesexportisaveoptions}
将多个相同格式的 PowerPoint 演示文稿合并为一个演示文稿文件。

```python
@staticmethod
def process(input_file_names, output_file_name, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| input_file_names | **List[str]** | 输入演示文稿文件名的数组。 |
| output_file_name | **str** | 合并后生成的演示文稿文件的输出文件名。 |
| options | [`ISaveOptions`](/slides/python-net/zh/aspose.slides.export/isaveoptions) | 定义合并后演示文稿保存方式的其他选项。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 当输入文件名无效或格式不匹配时抛出。 |

## process(input_file_names, output_stream, options) {#liststr-iorawiobase-asposeslidesexportisaveoptions}
将多个相同格式的 PowerPoint 演示文稿合并为一个演示文稿文件。

```python
@staticmethod
def process(input_file_names, output_stream, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| input_file_names | **List[str]** | 输入演示文稿文件名的数组。 |
| output_stream | **io.RawIOBase** | 输出流。 |
| options | [`ISaveOptions`](/slides/python-net/zh/aspose.slides.export/isaveoptions) | 定义合并后演示文稿保存方式的其他选项。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | 当输入文件名无效或格式不匹配时抛出。 |

### 另请参见
* 类 [`ISaveOptions`](/slides/python-net/zh/aspose.slides.export/isaveoptions)
* 类 [`Merger`](/slides/python-net/zh/aspose.slides.lowcode/merger)
* 模块 [`aspose.slides.lowcode`](/slides/python-net/zh/aspose.slides.lowcode)
* 库 [`Aspose.Slides`](/slides/python-net)