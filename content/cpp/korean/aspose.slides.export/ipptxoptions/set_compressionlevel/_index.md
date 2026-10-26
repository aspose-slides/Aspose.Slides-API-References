---
title: set_CompressionLevel()
second_title: Aspose.Slides for C++ API 참조
description: "프레젠테이션 문서를 저장할 때 사용되는 압축 수준을 지정합니다. 기본값은 CompressionLevel::Level6입니다."
type: docs
weight: 92
url: /ko/aspose.slides.export/ipptxoptions/set_compressionlevel/
---
## IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel) method

프레젠테이션 문서를 저장할 때 사용되는 압축 수준을 지정합니다. 기본값은 [CompressionLevel::Level6](../../compressionlevel/)입니다.

```cpp
virtual void Aspose::Slides::Export::IPptxOptions::set_CompressionLevel(Aspose::Slides::Export::CompressionLevel value)=0
```

## 비고

높은 압축 수준은 파일 크기를 더 작게 만들지만 처리 시간이 더 오래 걸립니다. 실제 압축 비율은 프레젠테이션 내용에 따라 달라집니다.

예시:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## 참조

* 열거형 [CompressionLevel](../../compressionlevel/)
* 클래스 [IPptxOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)