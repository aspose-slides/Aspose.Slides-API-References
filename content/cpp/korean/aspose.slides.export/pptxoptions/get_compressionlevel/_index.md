---
title: get_CompressionLevel()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "프레젠테이션 문서를 저장할 때 사용되는 압축 수준을 지정합니다. 기본값은 CompressionLevel::Level6입니다."
type: docs
weight: 79
url: /ko/aspose.slides.export/pptxoptions/get_compressionlevel/
---
## PptxOptions::get_CompressionLevel() 메서드


프레젠테이션 문서를 저장할 때 사용되는 압축 수준을 지정합니다. 기본값은 [CompressionLevel::Level6](../../compressionlevel/)입니다.

```cpp
Aspose::Slides::Export::CompressionLevel Aspose::Slides::Export::PptxOptions::get_CompressionLevel() override
```

## 비고


높은 압축 수준은 파일 크기를 줄이지만 처리 시간이 더 오래 걸립니다. 실제 압축 비율은 프레젠테이션의 내용에 따라 달라집니다.

예제: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");
System::SharedPtr<PptxOptions> pptxOptions = System::MakeObject<PptxOptions>();
pptxOptions->set_CompressionLevel(CompressionLevel::Level8);
pres->Save(u"demo-level8.pptx", SaveFormat::Pptx, pptxOptions);
```

## 참고

* 열거형 [CompressionLevel](../../compressionlevel/)
* 클래스 [PptxOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)