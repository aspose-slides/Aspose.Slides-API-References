---
title: set_DefaultRegularFont()
second_title: Aspose.Slides for C++ API Referansı
description: "Kaynak yazı tipi bulunamadığında kullanılan yazı tipini ayarlar. System::String yazar."
type: docs
weight: 66
url: /tr/aspose.slides.export/saveoptions/set_defaultregularfont/
---
## SaveOptions::set_DefaultRegularFont(System::String) metot


Kaynak yazı tipi bulunamadığında kullanılan yazı tipini ayarlar. [System::String](../../../system/string/) yazar.

```cpp
void Aspose::Slides::Export::SaveOptions::set_DefaultRegularFont(System::String value) override
```

## Açıklamalar



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

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [SaveOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)