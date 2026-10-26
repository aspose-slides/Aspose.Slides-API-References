---
title: IAudio class
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/iaudio/
---
## IAudio 类

表示嵌入的音频文件。

IAudio 类型公开以下成员：

## 属性

| Property | Description |
| :- | :- |
| [`content_type`](/slides/python-net/zh/aspose.slides/iaudio/content_type/) | Returns a MIME type of an audio, encoded in [`IAudio.binary_data`](/slides/python-net/zh/aspose.slides/iaudio/binary_data).<br/>            Read-only **str**. |
| [`binary_data`](/slides/python-net/zh/aspose.slides/iaudio/binary_data/) | Returns the copy of an audio's data. In case of large amount of data consider <br/>            using of [`IAudio.get_stream`](/slides/python-net/zh/aspose.slides/iaudio/get_stream) method to prevent unnecessary  loading of audio's<br/>            data into memory or even OutOfMemoryException.<br/>            Read-only **int**[]. |

## 方法

| Method | Description |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/zh/aspose.slides/iaudio/get_stream/#) | Returns Stream stream for reading.<br/>            Use 'using' or close stream after using. |


### 另请参见
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)