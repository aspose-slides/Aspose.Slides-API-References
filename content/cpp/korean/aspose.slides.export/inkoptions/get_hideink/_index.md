---
title: get_HideInk()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 내보낸 문서에서 Ink 요소를 표시하거나 숨깁니다.
type: docs
weight: 1
url: /ko/aspose.slides.export/inkoptions/get_hideink/
---
## InkOptions::get_HideInk() 메서드

내보낸 문서에서 [Ink](../../../aspose.slides.ink/) 요소를 표시하거나 숨깁니다.

```cpp
bool Aspose::Slides::Export::InkOptions::get_HideInk() override
```

## 비고

기본값은 false 입니다.

다음 예제는 내보낸 PDF 문서에서 [Ink](../../../aspose.slides.ink/) 요소를 숨기는 방법을 보여줍니다:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
pdfOptions->get_InkOptions()->set_HideInk(true);
pres->Save(u"output.pptx", SaveFormat::Pdf, pdfOptions);
```

## 참조

* 클래스 [InkOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* 라이브러리 [Aspose.Slides](../../../)