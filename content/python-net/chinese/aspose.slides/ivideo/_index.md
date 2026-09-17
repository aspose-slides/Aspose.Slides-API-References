---
title: IVideo class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ivideo/
---
## IVideo 类

表示嵌入到演示文稿中的视频。

IVideo 类型公开以下成员：

## 属性

| 属性 | 描述 |
| :- | :- |
| [`content_type`](/slides/python-net/zh/aspose.slides/ivideo/content_type/) | 返回视频的 MIME 类型，使用 [`IVideo.binary_data`](/slides/python-net/zh/aspose.slides/ivideo/binary_data) 编码。<br/>只读 **str**. |
| [`binary_data`](/slides/python-net/zh/aspose.slides/ivideo/binary_data/) | 返回音频数据的副本。对于大量数据的情况，请考虑使用<br/>[`IVideo.get_stream`](/slides/python-net/zh/aspose.slides/ivideo/get_stream) 方法以防止不必要地将视频数据加载到内存中<br/>甚至导致 OutOfMemoryException。<br/>只读 **int**[]. |

## 方法

| 方法 | 描述 |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/zh/aspose.slides/ivideo/get_stream/#) | 返回用于读取的 Stream 流。<br/>使用 'using'，或在使用后关闭流。 |


### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)