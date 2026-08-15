---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API 參考
description: True 代表將簡報中使用的所有 metafile 轉換為 PNG 圖像。讀取 bool.
type: docs
weight: 326
url: /zh-hant/aspose.slides.export/pdfoptions/get_savemetafilesaspng/
---
## PdfOptions::get_SaveMetafilesAsPng() 方法


True 要將簡報中使用的所有 metafiles 轉換為 PNG 圖像。讀取 **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_SaveMetafilesAsPng() override
```

## 備註


預設為 **true**。Pdf 文件可以包含向量圖形和點陣圖像。如果 SaveMetafilesAsPng 設為 true，則來源 Metafile 圖像會被轉換為 Png 格式，並儲存為 Pdf 的點陣圖像。如果 SaveMetafilesAsPng 設為 false，則來源 Metafile 會被轉換為 Pdf 向量圖形。每種方法都有其優點與缺點。例如，若 Metafile 轉換為 PNG，則在後續文件縮放時可能會有品質損失。若 Metafile 轉換為 Pdf 向量圖形，則在 Pdf 檢視工具中可能會出現效能問題。 
## 參見

* 類別 [PdfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)