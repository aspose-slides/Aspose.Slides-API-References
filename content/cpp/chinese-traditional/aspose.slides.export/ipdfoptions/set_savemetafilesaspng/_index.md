---
title: set_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API 參考
description: True 表示將簡報中使用的所有中繼檔案轉換為 PNG 圖像。寫入 bool.
type: docs
weight: 300
url: /zh-hant/aspose.slides.export/ipdfoptions/set_savemetafilesaspng/
---
## IPdfOptions::set_SaveMetafilesAsPng(bool) 方法


True 表示將簡報中使用的所有中繼檔案轉換為 PNG 圖像。寫入 **bool**。

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SaveMetafilesAsPng(bool value)=0
```

## 備註


預設值為 **true**。Pdf 文件可以包含向量圖形和點陣圖像。如果 SaveMetafilesAsPng 設為 true，則來源 Metafile 圖像會被轉換為 Png 格式，並作為點陣圖像儲存到 Pdf 中。如果 SaveMetafilesAsPng 設為 false，則來源 Metafile 會被轉換為 Pdf 向量圖形。每種方法都有其優點與缺點。例如，若將 Metafile 轉換為 PNG，則在最終文件縮放時可能會有品質損失。若將 Metafile 轉換為 Pdf 向量圖形，則在 Pdf 檢視工具中可能會出現效能問題。 
## 另請參閱

* 類別 [IPdfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 程式庫 [Aspose.Slides](../../../)