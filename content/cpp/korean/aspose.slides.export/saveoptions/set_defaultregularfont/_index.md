---
title: set_DefaultRegularFont()
second_title: Aspose.Slides C++ API 레퍼런스
description: "소스 글꼴을 찾을 수 없는 경우 사용되는 글꼴을 설정합니다. System::String을 기록합니다."
type: docs
weight: 66
url: /ko/aspose.slides.export/saveoptions/set_defaultregularfont/
---
## SaveOptions::set_DefaultRegularFont(System::String) 메서드



소스 글꼴을 찾을 수 없는 경우 사용되는 글꼴을 설정합니다. [System::String](../../../system/string/)를 기록합니다.

```cpp
void Aspose::Slides::Export::SaveOptions::set_DefaultRegularFont(System::String value) override
```

## 비고



```cpp
auto pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto htmlOpts = System::MakeObject<HtmlOptions>();
htmlOpts->set_DefaultRegularFont(u"Arial Black");
pres->Save(u"SomePresentation-out-ArialBlack.html", Aspose::Slides::Export::SaveFormat::Html, htmlOpts);
htmlOpts->set_DefaultRegularFont(u"Lucida Console");
pres->Save(u"Somepresentation-out-LucidaConsole.html", Aspose::Slides::Export::SaveFormat::Html, htmlOpts);

auto pdfOpts = System::MakeObject<PdfOptions>();
pdfOpts->set_DefaultRegularFont(u"Arial Black");
pres->Save(u"SomePresentation-out-ArialBlack.pdf", Aspose::Slides::Export::SaveFormat::Pdf, pdfOpts);
```

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [SaveOptions](../)
* 네임스페이스 [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)