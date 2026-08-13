---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 브러시를 렌더링하기 위해 ROP 연산 또는 불투명도를 사용합니다.
type: docs
weight: 40
url: /ko/aspose.slides.export/iinkoptions/set_interpretmaskopasopacity/
---
## IInkOptions::set_InterpretMaskOpAsOpacity(bool) method


브러시를 렌더링하기 위해 ROP 연산 또는 불투명도를 사용합니다.

```cpp
virtual void Aspose::Slides::Export::IInkOptions::set_InterpretMaskOpAsOpacity(bool value)=0
```

## 비고


기본값은 true입니다. 

다음 예제는 [Ink](../../../aspose.slides.ink/) 요소를 내보내기 위해 ROP를 사용하여 설정하는 방법을 보여줍니다. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 관련 항목

* 클래스 [IInkOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)