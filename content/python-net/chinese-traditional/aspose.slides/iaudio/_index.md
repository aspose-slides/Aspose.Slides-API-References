---
title: IAudio class
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/iaudio/
---
## IAudio 類別

表示嵌入的音訊檔案。

IAudio 類型提供以下成員：

## 屬性

| Property | Description |
| :- | :- |
| [`content_type`](/slides/python-net/zh-hant/aspose.slides/iaudio/content_type/) | 傳回音訊的 MIME 類型，編碼為 [`IAudio.binary_data`](/slides/python-net/zh-hant/aspose.slides/iaudio/binary_data)。<br/>            唯讀 **str**. |
| [`binary_data`](/slides/python-net/zh-hant/aspose.slides/iaudio/binary_data/) | 傳回音訊資料的副本。若資料量龐大，請考慮 <br/>            使用 [`IAudio.get_stream`](/slides/python-net/zh-hant/aspose.slides/iaudio/get_stream) 方法，以防止不必要的將音訊資料<br/>            載入記憶體，甚至引發 OutOfMemoryException。<br/>            唯讀 **int**[]. |

## 方法

| Method | Description |
| :- | :- |
| [`get_stream(self)`](/slides/python-net/zh-hant/aspose.slides/iaudio/get_stream/#) | 傳回用於讀取的 Stream 流。<br/>            使用 'using' 或在使用後關閉串流. |


### 另請參閱
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)