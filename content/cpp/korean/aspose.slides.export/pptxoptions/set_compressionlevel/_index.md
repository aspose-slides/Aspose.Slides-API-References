---
title: set_CompressionLevel()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "프레젠테이션 문서를 저장할 때 사용되는 압축 수준을 지정합니다. 기본값은 CompressionLevel::Level6입니다."
type: docs
weight: 92
url: /ko/aspose.slides.export/pptxoptions/set_compressionlevel/
---
## PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) 메서드


프레젠테이션 문서를 저장할 때 사용되는 압축 수준을 지정합니다. 기본값은 [CompressionLevel::Level6](../../compressionlevel/)입니다.

```cpp
void Aspose::Slides::Export::PptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value) override
```

## 비고


높은 압축 수준은 파일 크기를 더 작게 만들지만 처리 시간이 더 많이 소요됩니다. 실제 압축 비율은 프레젠테이션 내용에 따라 달라집니다.

예:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## 참고

* Enum [CompressionLevel](../../compressionlevel/)
* Class [PptxOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)