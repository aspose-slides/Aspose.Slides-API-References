---
title: get_SufficientResolution()
second_title: Aspose.Slides for C++ API 參考
description: 傳回決定 PDF 文件中圖像解析度的值。
type: docs
weight: 352
url: /zh-hant/aspose.slides.export/pdfoptions/get_sufficientresolution/
---
## PdfOptions::get_SufficientResolution() 方法

傳回決定 PDF 文件中圖像解析度的值。

```cpp
float Aspose::Slides::Export::PdfOptions::get_SufficientResolution() override
```

## 備註

屬性會影響檔案大小、匯出時間和圖像品質。

預設值是 **96**。

此參數的效果取決於少數因素。演算法會根據屬性值、原始圖像大小與圖像框大小，嘗試獲得最佳的輸出圖像尺寸。使用相似的屬性值可能會得到相同的結果。建議使用 16 或 32 的步長以獲得明顯的效果。

讀取 **float**. 
## 參見

* 類別 [PdfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)