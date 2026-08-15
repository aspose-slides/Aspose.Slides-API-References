---
title: get_SufficientResolution()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回一個決定 PDF 文件內圖像解析度的值。
type: docs
weight: 313
url: /zh-hant/aspose.slides.export/ipdfoptions/get_sufficientresolution/
---
## IPdfOptions::get_SufficientResolution() 方法

傳回一個決定 PDF 文件內圖像解析度的值。

```cpp
virtual float Aspose::Slides::Export::IPdfOptions::get_SufficientResolution()=0
```

## 備註

屬性會影響檔案大小、匯出時間和圖像品質。

預設值為 **96**。

此參數的效果取決於幾個因素。演算法會根據屬性值、來源圖像大小和圖像框架大小來取得最佳的輸出圖像尺寸。使用相似的屬性值可能會得到相同的結果。建議使用 16 或 32 的步長以獲得明顯的效果。

讀取 **float**. 
## 另請參閱

* 類別 [IPdfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)