---
title: set_InterpretMaskOpAsOpacity()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 브러시 렌더링에 ROP 연산 또는 불투명도를 사용합니다.
type: docs
weight: 40
url: /ko/aspose.slides.export/inkoptions/set_interpretmaskopasopacity/
---
## InkOptions::set_InterpretMaskOpAsOpacity(bool) 메서드


브러시 렌더링에 ROP 연산 또는 Opacity를 사용합니다.

```cpp
void Aspose::Slides::Export::InkOptions::set_InterpretMaskOpAsOpacity(bool value) override
```

## 비고

기본값은 true입니다. 

다음 예제는 [Ink](../../../aspose.slides.ink/) 요소에 대해 ROP를 사용하여 설정하는 방법을 보여줍니다: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_InterpretMaskOpAsOpacity(false);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 참고

* 클래스 [InkOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)