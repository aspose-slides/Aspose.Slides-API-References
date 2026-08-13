---
title: set_BwConversionMode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "컬러 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다. 이 옵션은 ITiffOptions::get_CompressionType()가 TiffCompressionTypes::CCITT4 또는 TiffCompressionTypes::CCITT3 Write BlackWhiteConversionMode 로 설정된 경우에만 적용됩니다. 기본값은 BlackWhiteConversionMode::Default 입니다."
type: docs
weight: 209
url: /ko/aspose.slides.export/tiffoptions/set_bwconversionmode/
---
## TiffOptions::set_BwConversionMode(BlackWhiteConversionMode) 메서드

컬러 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다. 이 옵션은 [ITiffOptions::get_CompressionType()](../../itiffoptions/get_compressiontype/)가 [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) 또는 [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) Write [BlackWhiteConversionMode](../../blackwhiteconversionmode/) 로 설정된 경우에만 적용됩니다. 기본값은 [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/) 입니다.

```cpp
void Aspose::Slides::Export::TiffOptions::set_BwConversionMode(BlackWhiteConversionMode value) override
```

## 비고

다음 예제는 변환 알고리즘을 Dithering 로 설정하는 방법을 보여줍니다.

```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## 참조

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Class [TiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)