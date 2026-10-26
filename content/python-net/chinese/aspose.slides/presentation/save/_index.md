---
title: save method
second_title: Aspose.Slides 用于 Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/presentation/save/
weight: 90
---
## save(self, options) {#asposeslidesexportxamlixamloptions}
将演示文稿的所有幻灯片保存为一组表示 XAML 标记的文件。

```python
def save(self, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [`IXamlOptions`](/slides/python-net/zh/aspose.slides.export.xaml/ixamloptions) | XAML 格式选项。 |

## save(self, fname, format) {#str-asposeslidesexportsaveformat}
将演示文稿的所有幻灯片保存为指定格式的文件。

```python
def save(self, fname, format):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| fname | **str** | 已创建文件的路径。 |
| format | [`SaveFormat`](/slides/python-net/zh/aspose.slides.export/saveformat) | 导出数据的格式。 |

## save(self, stream, format) {#iorawiobase-asposeslidesexportsaveformat}
将演示文稿的所有幻灯片保存到指定格式的流中。

```python
def save(self, stream, format):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 输出流。 |
| format | [`SaveFormat`](/slides/python-net/zh/aspose.slides.export/saveformat) | 导出数据的格式。 |

## save(self, fname, format, options) {#str-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}

```python
def save(self, fname, format, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| fname | **str** |  |
| format | [`SaveFormat`](/slides/python-net/zh/aspose.slides.export/saveformat) |  |
| options | [`ISaveOptions`](/slides/python-net/zh/aspose.slides.export/isaveoptions) |  |

## save(self, stream, format, options) {#iorawiobase-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
将演示文稿的所有幻灯片保存到指定格式的流中，并使用附加选项。

```python
def save(self, stream, format, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 输出流。 |
| format | [`SaveFormat`](/slides/python-net/zh/aspose.slides.export/saveformat) | 导出数据的格式。 |
| options | [`ISaveOptions`](/slides/python-net/zh/aspose.slides.export/isaveoptions) | 附加格式选项。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(NotSupportedException))** | 如果尝试在非 Office 2007-2010 格式下保存加密文件<br/>非 Office 2007-2010 格式 |

## save(self, fname, slides, format) {#str-listint-asposeslidesexportsaveformat}
将演示文稿的指定幻灯片保存为具有页面编号保留的指定格式文件。

```python
def save(self, fname, slides, format):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| fname | **str** | 已创建文件的路径。 |
| slides | **List[int]** | 包含幻灯片位置的数组，从 1 开始。 |
| format | [`SaveFormat`](/slides/python-net/zh/aspose.slides.export/saveformat) | 导出数据的格式。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 当 stream 或 slides 参数为 None 时。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 当 slides 参数包含错误的页码时。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 当使用不支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

## save(self, stream, slides, format) {#iorawiobase-listint-asposeslidesexportsaveformat}
将演示文稿的指定幻灯片保存到具有页面编号保留的指定格式流中。

```python
def save(self, stream, slides, format):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 输出流。 |
| slides | **List[int]** | 包含幻灯片位置的数组，从 1 开始。 |
| format | [`SaveFormat`](/slides/python-net/zh/aspose.slides.export/saveformat) | 导出数据的格式。 |

## save(self, fname, slides, format, options) {#str-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
将演示文稿的指定幻灯片保存为具有页面编号保留的指定格式文件。

```python
def save(self, fname, slides, format, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| fname | **str** | 已创建文件的路径。 |
| slides | **List[int]** | 包含幻灯片位置的数组，从 1 开始。 |
| format | [`SaveFormat`](/slides/python-net/zh/aspose.slides.export/saveformat) | 导出数据的格式。 |
| options | [`ISaveOptions`](/slides/python-net/zh/aspose.slides.export/isaveoptions) | 附加格式选项。 |

## save(self, stream, slides, format, options) {#iorawiobase-listint-asposeslidesexportsaveformat-asposeslidesexportisaveoptions}
将演示文稿的指定幻灯片保存到具有页面编号保留的指定格式流中。

```python
def save(self, stream, slides, format, options):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | **io.RawIOBase** | 输出流。 |
| slides | **List[int]** | 包含幻灯片位置的数组，从 1 开始。 |
| format | [`SaveFormat`](/slides/python-net/zh/aspose.slides.export/saveformat) | 导出数据的格式。 |
| options | [`ISaveOptions`](/slides/python-net/zh/aspose.slides.export/isaveoptions) | 附加格式选项。 |

### 异常

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 当 stream 或 slides 参数为 None 时。 |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | 当 slides 参数包含错误的页码时。 |
| **RuntimeError(Proxy error(InvalidOperationException))** | 当使用不支持的 SaveFormat 时，例如 PPTX、PPTM、PPSX、PPSM、POTX、POTM、PPT、ODP。 |

### 另请参阅
* 类 [`ISaveOptions`](/slides/python-net/zh/aspose.slides.export/isaveoptions)
* 类 [`IXamlOptions`](/slides/python-net/zh/aspose.slides.export.xaml/ixamloptions)
* 类 [`Presentation`](/slides/python-net/zh/aspose.slides/presentation)
* 枚举 [`SaveFormat`](/slides/python-net/zh/aspose.slides.export/saveformat)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)