---
title: get_DefaultRegularFont()
second_title: Aspose.Slides for C++ API Referansı
description: "Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür. System::String okur."
type: docs
weight: 53
url: /tr/aspose.slides.export/isaveoptions/get_defaultregularfont/
---
## ISaveOptions::get_DefaultRegularFont() yöntem


Kaynak yazı tipi bulunamadığında kullanılan yazı tipini döndürür. Okur [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::ISaveOptions::get_DefaultRegularFont()=0
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

## Ayrıca bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [ISaveOptions](../)
* Ad alanı [Aspose::Slides::Export](../../)
* Kütüphane [Aspose.Slides](../../../)