---
title: get_DefaultRegularFont()
second_title: Aspose.Slides برای C++ مرجع API
description: "قلمی را برمی‌گرداند که در صورتی که قلم منبع پیدا نشود استفاده می‌شود. System::String را می‌خواند."
type: docs
weight: 53
url: /fa/aspose.slides.export/isaveoptions/get_defaultregularfont/
---
## ISaveOptions::get_DefaultRegularFont() متد


قلمی را برمی‌گرداند که در صورتی که قلم منبع پیدا نشود استفاده می‌شود. [System::String](../../../system/string/) را می‌خواند.

```cpp
virtual System::String Aspose::Slides::Export::ISaveOptions::get_DefaultRegularFont()=0
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

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [ISaveOptions](../)
* فضای‌نام [Aspose::Slides::Export](../../)
* کتابخانه [Aspose.Slides](../../../)