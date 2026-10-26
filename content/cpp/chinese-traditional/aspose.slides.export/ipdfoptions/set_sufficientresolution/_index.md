---
title: set_SufficientResolution()
second_title: Aspose.Slides for C++ API 參考
description: 設定一個用於決定 PDF 文件內圖像解析度的值。
type: docs
weight: 326
url: /zh-hant/aspose.slides.export/ipdfoptions/set_sufficientresolution/
---
## IPdfOptions::set_SufficientResolution(float) 方法


設定一個用於決定 PDF 文件內圖像解析度的值。

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_SufficientResolution(float value)=0
```

## 備註


此屬性會影響檔案大小、匯出時間與圖像品質。

預設值為 **96**。

此參數的效果取決於幾個因素。演算法會根據屬性值、來源圖像大小和圖像框架大小來取得最佳輸出圖像尺寸。使用相似的屬性值可能會得到相同的結果。建議使用 16 或 32 的步長以獲得明顯效果。

寫入 **float**。 
## 另見

* 類別 [IPdfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)