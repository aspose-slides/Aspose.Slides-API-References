---
title: get_BwConversionMode()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "컬러 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다. 이 옵션은 ITiffOptions::get_CompressionType()가 TiffCompressionTypes::CCITT4 또는 TiffCompressionTypes::CCITT3 로 설정된 경우에만 적용됩니다. BlackWhiteConversionMode을 읽어보십시오. 기본값은 BlackWhiteConversionMode::Default입니다."
type: docs
weight: 183
url: /ko/aspose.slides.export/itiffoptions/get_bwconversionmode/
---
## ITiffOptions::get_BwConversionMode() 메서드

컬러 이미지를 흑백 이미지로 변환하는 알고리즘을 지정합니다. 이 옵션은 [ITiffOptions::get_CompressionType()](../get_compressiontype/)가 [TiffCompressionTypes::CCITT4](../../tiffcompressiontypes/) 또는 [TiffCompressionTypes::CCITT3](../../tiffcompressiontypes/) 로 설정된 경우에만 적용됩니다. [BlackWhiteConversionMode](../../blackwhiteconversionmode/)를 참조하십시오. 기본값은 [BlackWhiteConversionMode::Default](../../blackwhiteconversionmode/)입니다.

```cpp
virtual BlackWhiteConversionMode Aspose::Slides::Export::ITiffOptions::get_BwConversionMode()=0
```

## 비고

다음 예제는 변환 알고리즘을 Dithering으로 설정하는 방법을 보여줍니다.
```cpp
System::SharedPtr<TiffOptions> tiffOptions = System::MakeObject<TiffOptions>();
tiffOptions->set_CompressionType(TiffCompressionTypes::CCITT4);
tiffOptions->set_BwConversionMode(BlackWhiteConversionMode::Dithering);

System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();
presentation->Save(tiffFilePath, SaveFormat::Tiff, tiffOptions);
```

## 참고

* Enum [BlackWhiteConversionMode](../../blackwhiteconversionmode/)
* Class [ITiffOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)