---
title: get_DefaultRegularFont()
second_title: مرجع API Aspose.Slides للغة C++
description: "يرجع الخط المستخدم في حال عدم العثور على خط المصدر. يقرأ System::String."
type: docs
weight: 53
url: /ar/aspose.slides.export/isaveoptions/get_defaultregularfont/
---
## ISaveOptions::get_DefaultRegularFont() طريقة

يرجع الخط المستخدم في حال عدم العثور على خط المصدر. يقرأ [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::ISaveOptions::get_DefaultRegularFont()=0
```

## ملاحظات

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

## انظر أيضًا

* فئة [String](../../../system/string/)
* فئة [ISaveOptions](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)