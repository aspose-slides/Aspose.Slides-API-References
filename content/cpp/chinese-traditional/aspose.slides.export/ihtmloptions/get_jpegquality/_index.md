---
title: get_JpegQuality()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回一個決定 PDF 文件內 JPEG 圖片品質的值。讀取 uint8_t。
type: docs
weight: 79
url: /zh-hant/aspose.slides.export/ihtmloptions/get_jpegquality/
---
## IHtmlOptions::get_JpegQuality() 方法

傳回一個決定 PDF 文件內 JPEG 圖片品質的值。讀取 **uint8_t**。

```cpp
virtual uint8_t Aspose::Slides::Export::IHtmlOptions::get_JpegQuality()=0
```

## 備註

僅在文件包含 JPEG 圖片時才會產生作用。

在保存為 PDF 格式時，使用此屬性取得或設定文件內圖像的品質。此數值可在 0 至 100 之間變動，其中 0 代表最差品質但最高壓縮，100 代表最佳品質但最低壓縮。

預設值為 **95**。

## 另見

* 類別 [IHtmlOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 程式庫 [Aspose.Slides](../../../)