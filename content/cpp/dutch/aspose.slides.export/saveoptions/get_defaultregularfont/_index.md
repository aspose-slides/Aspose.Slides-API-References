---
title: get_DefaultRegularFont()
second_title: Aspose.Slides voor C++ API-referentie
description: "Retourneert het lettertype dat wordt gebruikt wanneer het bronlettertype niet wordt gevonden. Leest System::String."
type: docs
weight: 53
url: /nl/aspose.slides.export/saveoptions/get_defaultregularfont/
---
## SaveOptions::get_DefaultRegularFont() methode

Retourneert het lettertype dat wordt gebruikt als het bronlettertype niet wordt gevonden. Leest [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::SaveOptions::get_DefaultRegularFont() override
```

## Opmerkingen



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

## Zie ook

* Klasse [String](../../../system/string/)
* Klasse [SaveOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)