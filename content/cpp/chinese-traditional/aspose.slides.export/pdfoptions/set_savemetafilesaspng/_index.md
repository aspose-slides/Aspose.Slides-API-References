---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API 參考文件
description: 若為 true，將簡報中使用的所有中繪檔轉換為 PNG 圖像。寫入 bool。
type: docs
weight: 339
url: /zh-hant/aspose.slides.export/pdfoptions/set_savemetafilesaspng/
---
## PdfOptions::set_SaveMetafilesAsPng(bool) 方法

若為 true 時，將簡報中使用的所有中繪檔轉換為 PNG 圖像。寫入 **bool**。

```cpp
void Aspose::Slides::Export::PdfOptions::set_SaveMetafilesAsPng(bool value) override
```

## 備註

預設為 **true**。Pdf 文件可以包含向量圖形和點陣圖像。如果 SaveMetafilesAsPng 設為 true，則來源 Metafile 圖像會被轉換為 Png 格式，並以點陣圖像儲存至 Pdf。如果 SaveMetafilesAsPng 設為 false，則來源 Metafile 會被轉換為 Pdf 向量圖形。每種方法皆有其優缺點。例如，若 Metafile 轉換為 PNG，則在對最終文件縮放時可能會出現品質損失。若 Metafile 轉換為 Pdf 向量圖形，則在 Pdf 檢視工具中可能出現效能問題。

## 另請參閱

* 類別 [PdfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)