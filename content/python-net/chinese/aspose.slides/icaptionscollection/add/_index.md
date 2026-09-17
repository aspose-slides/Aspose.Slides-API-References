---
title: add method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/icaptionscollection/add/
weight: 10
---
## add(self, label, file_path) {#str-str}
将 WebVTT 闭合字幕添加到集合的末尾。

### Returns

已添加的 [`ICaptions`](/slides/python-net/zh/aspose.slides/icaptions) 实例。



```python
def add(self, label, file_path):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| label | **str** | 闭合字幕的标签。 |
| file_path | **str** | WebVTT 文件的路径。 |

### Exceptions

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 如果 `file_path` 为 `None`，则抛出。 |
| **RuntimeError(Proxy error(ArgumentException))** | 如果 `file_path` 为空，则抛出。 |


## add(self, label, stream) {#str-iorawiobase}
从流中将 WebVTT 闭合字幕添加到集合的末尾。

### Returns

已添加的 [`ICaptions`](/slides/python-net/zh/aspose.slides/icaptions) 实例。



```python
def add(self, label, stream):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| label | **str** | 闭合字幕的标签。 |
| stream | **io.RawIOBase** | 包含 WebVTT 格式数据的输入流。 |

### Exceptions

| 异常 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 如果 `stream` 为 `None`，则抛出。 |
| **RuntimeError(Proxy error(ArgumentException))** | 如果输入数据不是 WebVTT 格式，则抛出。 |



### See Also
* 类 [`ICaptions`](/slides/python-net/zh/aspose.slides/icaptions)
* 类 [`ICaptionsCollection`](/slides/python-net/zh/aspose.slides/icaptionscollection)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)