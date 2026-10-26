---
title: IVideo class
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ivideo/
---
## IVideo 類別

表示嵌入於簡報中的視訊。

IVideo 類型公開以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`content_type`](/slides/python-net/zh-hant/aspose.slides/ivideo/content_type/) | 傳回影片的 MIME 類型，編碼為 [`IVideo.binary_data`](/slides/python-net/zh-hant/aspose.slides/ivideo/binary_data)。<br/>            唯讀 **str**. |
| [`binary_data`](/slides/python-net/zh-hant/aspose.slides/ivideo/binary_data/) | 傳回音訊資料的副本。若資料量龐大，請考慮使用<br/>            [`IVideo.get_stream`](/slides/python-net/zh-hant/aspose.slides/ivideo/get_stream) 方法，以防止不必要地將影片資料載入記憶體<br/>            或導致 OutOfMemoryException。<br/>            唯讀 **int**[]. |

## 方法

| Method | Description |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/zh-hant/aspose.slides/ivideo/get_stream/#) | 傳回用於讀取的 Stream 流。<br/>            使用 'using' 或在使用後關閉串流. |


### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)