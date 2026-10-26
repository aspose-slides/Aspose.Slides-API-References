---
title: set_BwConversionMode()
second_title: Aspose.Slides for C++ API 參考文件
description: "指定將彩色影像轉換為黑白影像的演算法。此選項僅在 ITiffOptions::get_CompressionType() 設為 TiffCompressionTypes::CCITT4 或 TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode 時套用。預設為 BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /zh-hant/aspose.slides.export/itiffoptions/set_bwconversionmode/
---
## ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode) 方法


指定將彩色影像轉換為黑白影像的演算法。此選項僅在 [ITiffOptions::get_CompressionType()](../get_compressiontype/) 設為 [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) 或 [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/) 時套用。預設為 [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/).

```cpp
virtual void Aspose::Slides::Export::ITiffOptions::set_BwConversionMode(BlackWhiteConversionMode value)=0
```

## 備註


以下範例顯示如何將轉換演算法設定為 Dithering. 
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