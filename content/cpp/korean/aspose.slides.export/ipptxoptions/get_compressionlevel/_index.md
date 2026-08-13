---
title: get_CompressionLevel()
second_title: Aspose.Slides for C++ API 참조
description: "프레젠테이션 문서를 저장할 때 사용되는 압축 수준을 지정합니다. 기본값은 CompressionLevel::Level6입니다."
type: docs
weight: 79
url: /ko/aspose.slides.export/ipptxoptions/get_compressionlevel/
---
## IPptxOptions::get_CompressionLevel() 메서드

프레젠테이션 문서를 저장할 때 사용되는 압축 수준을 지정합니다. 기본값은 [CompressionLevel::Level6](../../compressionlevel/)입니다.

```cpp
virtual Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::IPptxOptions::get_CompressionLevel()=0
```

## 비고

높은 압축 수준은 파일 크기를 줄이지만 처리 시간이 더 많이 필요합니다. 실제 압축 비율은 프레젠테이션의 내용에 따라 달라집니다.

예:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## 참고

* 열거형 [CompressionLevel](../../compressionlevel/)
* 클래스 [IPptxOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)