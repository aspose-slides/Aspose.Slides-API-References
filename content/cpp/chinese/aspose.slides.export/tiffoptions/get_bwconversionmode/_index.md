---
title: get_BwConversionMode()
second_title: Aspose.Slides C++ API 参考
description: "指定用于将彩色图像转换为黑白图像的算法。此选项仅在 ITiffOptions::get_CompressionType() 设置为 TiffCompressionTypes::CCITT4 或 TiffCompressionTypes::CCITT3 阅读 BlackWhiteConversionMode 时应用。默认是 BlackWhiteConversionMode::Default."
type: docs
weight: 196
url: /zh/aspose.slides.export/tiffoptions/get_bwconversionmode/
---
## TiffOptions::get_BwConversionMode() 方法

指定将彩色图像转换为黑白图像的算法。此选项仅在 [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/) 设置为 [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) 或 [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) 读取 [BlackWhiteConversionMode](../../blackwhiteconversionmode/) 时应用。默认值为 [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/)。

```cpp
BlackWhiteConversionMode Aspose::Slides::Export::TiffOptions::get_BwConversionMode() override
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
## 参见

* 枚举 [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* 类 [TiffOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)