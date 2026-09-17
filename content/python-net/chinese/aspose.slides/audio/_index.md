---
title: Audio class
second_title: Aspose.Slides for Python via .NET API 参考文档
description: 
type: docs
url: /zh/aspose.slides/audio/
---
## Audio 类

表示嵌入的音频文件。

Audio 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`content_type`](/slides/python-net/zh/aspose.slides/audio/content_type/) | 返回音频的 MIME 类型，以 [`Audio.binary_data`](/slides/python-net/zh/aspose.slides/audio/binary_data) 编码。<br/>只读 **str**。 |
| [`binary_data`](/slides/python-net/zh/aspose.slides/audio/binary_data/) | 返回音频数据的副本。 在数据量大的情况下请考虑<br/>使用 [`Audio.get_stream`](/slides/python-net/zh/aspose.slides/audio/get_stream) 方法以防止不必要地将音频数据<br/>加载到内存中，甚至导致 OutOfMemoryException。<br/>只读 **int**[]. |

## 方法

| Method | Description |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/zh/aspose.slides/audio/get_stream/#) | 返回用于读取的 Stream 流。<br/>使用 'using'，或在使用后关闭流。 |

### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)