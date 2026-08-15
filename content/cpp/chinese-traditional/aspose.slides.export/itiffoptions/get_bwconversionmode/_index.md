---
title: get_BwConversionMode()
second_title: Aspose.Slides for C++ API 參考
description: "指定將彩色影像轉換為黑白影像的演算法。此選項僅在 ITiffOptions::get_CompressionType() 設為 TiffCompressionTypes::CCITT4 或 TiffCompressionTypes::CCITT3 時套用，請參閱 BlackWhiteConversionMode。預設為 BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /zh-hant/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() 方法

指定將彩色影像轉換為黑白影像的演算法。只有在 [ITiffOptions::get_CompressionType()](../get_compressiontype/) 設為 [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) 或 [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) 時才會套用此選項，請參閱 [BlackWhiteConversionMode](../../blackwhiteconversionmode/)。預設為 [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/)。

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
```

## 備註

以下範例示範如何將轉換演算法設為 Dithering。

```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## 另見

* 列舉 [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* 類別 [ITiffOptions](../)
* 命名空間 [Aspose::Slides::Export](../../)
* 函式庫 [Aspose.Slides](../../../)