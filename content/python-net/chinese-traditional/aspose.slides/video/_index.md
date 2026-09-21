---
title: Video class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/video/
---
## Video 類別

表示嵌入於簡報中的影像。

Video 類別公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`content_type`](/slides/python-net/zh-hant/aspose.slides/video/content_type/) | 傳回以 [`Video.binary_data`](/slides/python-net/zh-hant/aspose.slides/video/binary_data) 編碼的視訊 MIME 類型。<br/>            唯讀 **str**. |
| [`binary_data`](/slides/python-net/zh-hant/aspose.slides/video/binary_data/) | 傳回音訊資料的副本。若資料量大，請考慮使用<br/>            [`Video.get_stream`](/slides/python-net/zh-hant/aspose.slides/video/get_stream) 方法，以防止不必要地將視訊資料載入記憶體<br/>            或甚至發生 OutOfMemoryException。<br/>            唯讀 **int**[]. |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/zh-hant/aspose.slides/video/get_stream/#) | 傳回用於讀取的 Stream 流。<br/>            使用 'using' 或在使用後關閉流。 |


### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)