---
title: set_BwConversionMode()
second_title: Aspose.Slides for C++ API 参考
description: "指定将彩色图像转换为黑白图像的算法。仅当 ITiffOptions::get_CompressionType() 设置为 TiffCompressionTypes::CCITT4 或 TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode 时才会应用此选项。默认值为 BlackWhiteConversionMode::Default。"
type: docs
weight: 209
url: /zh/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) method

指定将彩色图像转换为黑白图像的算法。仅当 [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) 设置为 [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) 或 [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/) 时才会应用此选项。默认值为 [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/)。

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
```

## 备注

以下示例展示了如何将转换算法设置为 Dithering。 
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## 另见

* 枚举 [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* 类 [TiffOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)