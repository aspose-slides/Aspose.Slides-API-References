---
title: get_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 브러시를 렌더링할 때 ROP 연산 또는 불투명도를 사용합니다.
type: docs
weight: 27
url: /ko/aspose.slides.export/inkoptions/get_interpretmaskopasopacity/
---
## InkOptions::get_InterpretMaskOpAsOpacity() 메서드


브러시를 렌더링할 때 ROP 연산 또는 불투명도를 사용합니다.

```cpp
bool Aspose::Slides::Export::InkOptions::get_InterpretMaskOpAsOpacity() override
```

## 비고


기본값은 true 입니다. 

다음 예제는 [Ink](../../../aspose.slides.ink/) 요소를 내보내기 위해 ROP를 사용하여 설정하는 방법을 보여줍니다: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 참조

* 클래스 [InkOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)