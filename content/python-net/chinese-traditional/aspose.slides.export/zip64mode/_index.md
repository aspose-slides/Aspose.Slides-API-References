---
title: Zip64Mode enumeration
second_title: Aspose.Slides 用於 Python 透過 .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides.export/zip64mode/
---
## Zip64Mode 列舉

指定在何時對 OpenXML 檔案使用 ZIP64 格式擴充。

Zip64Mode 類型公開以下成員：

## 欄位

| 欄位 | 說明 |
| :- | :- |
| NEVER | 不使用 ZIP64 格式擴充。 |
| IF_NECESSARY | 如有必要則使用 ZIP64 格式擴充。 |
| ALWAYS | 一律使用 ZIP64 格式擴充。 |


### 備註

OpenXML 檔案是一個 ZIP 壓縮檔，對未壓縮的檔案大小限制為 4 GB（2^32 位元組），  
            壓縮後的檔案大小、壓縮檔總大小亦受此限制，且壓縮檔內的檔案數量上限為 65,535（2^16-1）個。  
            ZIP64 格式擴充將上限提升至 2^64。  


### 另請參閱
* 模組 [`aspose.slides.export`](/slides/python-net/zh-hant/aspose.slides.export)
* 函式庫 [`Aspose.Slides`](/slides/python-net)