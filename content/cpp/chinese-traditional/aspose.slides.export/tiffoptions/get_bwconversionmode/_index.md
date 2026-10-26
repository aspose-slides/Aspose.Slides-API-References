---
title: get_BwConversionMode()
second_title: Aspose.Slides for C++ API 參考
description: "指定將彩色圖像轉換為黑白圖像的演算法。此選項僅在 ITiffOptions::get_CompressionType() 設定為 TiffCompressionTypes::CCITT4 或 TiffCompressionTypes::CCITT3 時套用。請參閱 BlackWhiteConversionMode。預設為 BlackWhiteConversionMode::Default。"
type: docs
weight: 196
url: /zh-hant/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() 方法

指定將彩色圖像轉換為黑白圖像的算法。此選項僅在 [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) 設置為 [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) 或 [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) 讀取 [BlackWhiteConversionMode](../../blackwhiteconversionmode/) 時套用。預設為 [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/)。

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
```

## 備註

以下範例顯示如何將轉換算法設定為抖動。
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## 另請參閱

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* 類別 [TiffOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)