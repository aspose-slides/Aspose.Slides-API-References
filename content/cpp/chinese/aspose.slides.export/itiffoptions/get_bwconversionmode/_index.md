---
title: get_BwConversionMode()
second_title: Aspose.Slides for C++ API 参考
description: "指定将彩色图像转换为黑白图像的算法。仅当 ITiffOptions::get_CompressionType() 设置为 TiffCompressionTypes::CCITT4 或 TiffCompressionTypes::CCITT3 时才会应用此选项。阅读 BlackWhiteConversionMode。默认是 BlackWhiteConversionMode::Default."
type: docs
weight: 183
url: /zh/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() 方法

指定将彩色图像转换为黑白图像的算法。此选项仅在 [ITiffOptions::get_CompressionType()](../get_compressiontype/) 设置为 [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) 或 [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) 时才会应用。读取 [BlackWhiteConversionMode](../../blackwhiteconversionmode/)。默认是 [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/)。

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
```

## 备注

下面的示例展示了如何将转换算法设置为 Dithering。
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## 参见

* 枚举 [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* 类 [ITiffOptions](../)
* 命名空间 [Aspose::Slides::Export](../../)
* 库 [Aspose.Slides](../../../)