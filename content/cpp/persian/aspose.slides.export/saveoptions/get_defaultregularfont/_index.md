---
title: get_DefaultRegularFont()
second_title: Aspose.Slides برای C++ مرجع API
description: "فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود برمی‌گرداند. System::String را می‌خواند."
type: docs
weight: 53
url: /fa/aspose.slides.export/saveoptions/get_defaultregularfont/
---
## SaveOptions::get_DefaultRegularFont() متد

فونتی را که در صورت عدم یافتن فونت منبع استفاده می‌شود برمی‌گرداند. [System::String](../../../system/string/) را می‌خواند.

```cpp
System::String Aspose::Slides::Export::SaveOptions::get_DefaultRegularFont() override
```

## توضیحات

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

## همچنین ببینید

* کلاس [String](../../../system/string/)
* کلاس [SaveOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)