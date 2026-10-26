---
title: Audio class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/audio/
---
## Audio 類別

表示嵌入的音訊檔案。

Audio 類型公開以下成員：

## 屬性

| 屬性 | 說明 |
| :- | :- |
| [`content_type`](/slides/python-net/zh-hant/aspose.slides/audio/content_type/) | 返回音訊的 MIME 類型，編碼為 [`Audio.binary_data`](/slides/python-net/zh-hant/aspose.slides/audio/binary_data)。<br/>            唯讀 **str**. |
| [`binary_data`](/slides/python-net/zh-hant/aspose.slides/audio/binary_data/) | 返回音訊資料的副本。若資料量龐大，請考慮<br/>            使用 [`Audio.get_stream`](/slides/python-net/zh-hant/aspose.slides/audio/get_stream) 方法，以防止不必要的音訊資料<br/>            載入記憶體或甚至發生 OutOfMemoryException。<br/>            唯讀 **int**[]. |

## 方法

| 方法 | 說明 |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/zh-hant/aspose.slides/audio/get_stream/#) | 返回用於讀取的 Stream 流。<br/>            使用 'using' 或在使用後關閉流。 |

### 另見
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)