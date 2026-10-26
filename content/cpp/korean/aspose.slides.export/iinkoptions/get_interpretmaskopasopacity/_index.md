---
title: get_InterpretMaskOpAsOpacity()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 브러시를 렌더링하기 위해 ROP 연산 또는 불투명도를 사용합니다.
type: docs
weight: 27
url: /ko/aspose.slides.export/iinkoptions/get_interpretmaskopasopacity/
---
## IInkOptions::get_InterpretMaskOpAsOpacity() 메서드


브러시를 렌더링하기 위해 ROP 연산 또는 불투명도를 사용합니다.

```cpp
virtual bool Aspose::Slides::Export::IInkOptions::get_InterpretMaskOpAsOpacity()=0
```

## 비고


기본값은 true입니다. 

다음 예제는 ROP를 사용하여 [Ink](../../../aspose.slides.ink/) 요소를 내보내는 방법을 보여줍니다: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 참고

* 클래스 [IInkOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)