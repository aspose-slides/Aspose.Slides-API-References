---
title: Video class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/video/
---
## Video 类

表示嵌入到演示文稿中的图像。

Video 类型暴露以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`content_type`](/slides/python-net/zh/aspose.slides/video/content_type/) | 返回视频的 MIME 类型，使用 [`Video.binary_data`](/slides/python-net/zh/aspose.slides/video/binary_data) 编码。<br/>            只读 **str**。 |
| [`binary_data`](/slides/python-net/zh/aspose.slides/video/binary_data/) | 返回音频数据的副本。若数据量大，建议使用 <br/>            [`Video.get_stream`](/slides/python-net/zh/aspose.slides/video/get_stream) 方法，以防止不必要地将视频数据加载到内存中 <br/>            或导致 OutOfMemoryException。<br/>            只读 **int**[]。 |

## 方法

| Method | Description |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/zh/aspose.slides/video/get_stream/#) | 返回用于读取的 Stream 流。<br/>            使用 'using' 或在使用后关闭流。 |

### 另见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)