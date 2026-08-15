---
title: set_SufficientResolution()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定決定 PDF 文件中圖像解析度的值。
type: docs
weight: 365
url: /zh-hant/aspose.slides.export/pdfoptions/set_sufficientresolution/
---
## PdfOptions::set_SufficientResolution(float) 方法

設定決定 PDF 文件中圖像解析度的值。

```cpp
void Aspose::Slides::Export::PdfOptions::set_SufficientResolution(float value) override
```

## 備註

屬性會影響檔案大小、匯出時間和圖像品質。

預設值為 **96**。

此參數的效果取決於幾個因素。演算法會根據屬性值、來源圖像大小與圖像框架大小，嘗試獲得最佳的輸出圖像尺寸。使用相似的屬性值可能會得到相同的結果。建議使用 16 或 32 的步距以獲得明顯的效果。

寫入 **float**。 
## 另見

* 類別 [PdfOptions](../)
* 名稱空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)