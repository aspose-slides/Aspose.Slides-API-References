---
title: get_SaveMetafilesAsPng()
second_title: Aspose.Slides for C++ API 參考
description: True 表示將簡報中使用的所有 metafile 轉換為 PNG 圖像。讀取 bool。
type: docs
weight: 287
url: /zh-hant/aspose.slides.export/ipdfoptions/get_savemetafilesaspng/
---
## IPdfOptions::get_SaveMetafilesAsPng() 方法

True 代表將簡報中使用的所有 Metafile 轉換為 PNG 圖像。讀取 **bool**。

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_SaveMetafilesAsPng()=0
```

## 備註

預設為 **true**。Pdf 文檔可以包含向量圖形和點陣圖像。如果 SaveMetafilesAsPng 設定為 true，則來源 Metafile 圖像會轉換為 Png 格式，並以點陣圖像儲存到 Pdf。如果 SaveMetafilesAsPng 設定為 false，則來源 Metafile 會轉換為 Pdf 向量圖形。每種方法都有其優點與缺點。例如，如果 Metafile 轉換為 PNG，則在最終文件縮放時可能會出現品質損失。如果 Metafile 轉換為 Pdf 向量圖形，則 Pdf 查看工具可能會出現效能問題。

## 另見

* 類別 [IPdfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)