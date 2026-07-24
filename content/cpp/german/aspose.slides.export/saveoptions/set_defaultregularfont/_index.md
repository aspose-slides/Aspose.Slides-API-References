---
title: set_DefaultRegularFont()
second_title: Aspose.Slides für C++ API-Referenz
description: "Legt die Schriftart fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Schreibt System::String."
type: docs
weight: 66
url: /de/aspose.slides.export/saveoptions/set_defaultregularfont/
---
## SaveOptions::set_DefaultRegularFont(System::String) Methode


Legt die Schriftart fest, die verwendet wird, falls die Quellschriftart nicht gefunden wird. Schreibt [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::SaveOptions::set_DefaultRegularFont(System::String value) override
```

## Anmerkungen



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

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [SaveOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)