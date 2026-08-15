---
title: set_JpegQuality()
second_title: Aspose.Slides for C++ API 參考
description: 設定一個值，用於決定 PDF 文件中 JPEG 圖像的品質。寫入 uint8_t.
type: docs
weight: 92
url: /zh-hant/aspose.slides.export/ihtmloptions/set_jpegquality/
---
## IHtmlOptions::set_JpegQuality(uint8_t) 方法

設定一個值，用於決定 PDF 文件中 JPEG 圖像的品質。寫入 **uint8_t**。

```cpp
virtual void Aspose::Slides::Export::IHtmlOptions::set_JpegQuality(uint8_t value)=0
```

## 備註

僅在文件包含 JPEG 圖像時才會產生作用。

在以 PDF 格式儲存時，使用此屬性取得或設定文件內圖像的品質。該值可在 0 到 100 之間變化，其中 0 表示品質最差但壓縮最大，100 表示品質最佳但壓縮最小。

預設值為 **95**。

## 參見

* 類別 [IHtmlOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)