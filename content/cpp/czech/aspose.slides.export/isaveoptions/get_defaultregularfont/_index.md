---
title: get_DefaultRegularFont()
second_title: Aspose.Slides pro C++ API Reference
description: "Vrací písmo použité v případě, že výchozí písmo není nalezeno. Čte System::String."
type: docs
weight: 53
url: /cs/aspose.slides.export/isaveoptions/get_defaultregularfont/
---
## ISaveOptions::get_DefaultRegularFont() metoda

Vrací písmo použité v případě, že výchozí písmo není nalezeno. Čte [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Export::ISaveOptions::get_DefaultRegularFont()=0
```

## Poznámky

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

## Viz také

* Třída [String](../../../system/string/)
* Třída [ISaveOptions](../)
* Obor názvů [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)