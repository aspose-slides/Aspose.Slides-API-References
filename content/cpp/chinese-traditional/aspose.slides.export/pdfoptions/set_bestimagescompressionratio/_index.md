---
title: set_BestImagesCompressionRatio()
second_title: Aspose.Slides for C++ API 參考
description: 指示是否必須自動為每張圖像選擇最有效的壓縮（而非預設）。如果設定為 bool.true，簡報中的每張圖像都會選擇最合適的壓縮演算法，從而使生成的 PDF 文件大小更小。
type: docs
weight: 105
url: /zh-hant/aspose.slides.export/pdfoptions/set_bestimagescompressionratio/
---
## PdfOptions::set_BestImagesCompressionRatio(bool) 方法

指示是否必須自動選擇每張圖像的最有效壓縮（而非預設）。如果設定為 **bool**.true，則簡報中的每張圖像都會選擇最合適的壓縮演算法，從而使產生的 PDF 文件尺寸更小。

```cpp
void Aspose::Slides::Export::PdfOptions::set_BestImagesCompressionRatio(bool value) override
```

## 備註

最佳圖像壓縮比的選擇計算成本高，且會佔用額外的記憶體，且此選項預設為 **bool**.false。

預設為 **bool**.false。
## 另見

* 類別 [PdfOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)