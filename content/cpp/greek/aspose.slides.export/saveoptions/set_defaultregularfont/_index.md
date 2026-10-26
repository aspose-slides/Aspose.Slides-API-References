---
title: set_DefaultRegularFont()
second_title: Aspose.Slides για την τεκμηρίωση API C++
description: "Ορίζει τη γραμματοσειρά που χρησιμοποιείται όταν η γραμματοσειρά πηγής δεν βρεθεί. Γράφει System::String."
type: docs
weight: 66
url: /el/aspose.slides.export/saveoptions/set_defaultregularfont/
---
## SaveOptions::set_DefaultRegularFont(System::String) μέθοδος

Ορίζει τη γραμματοσειρά που χρησιμοποιείται όταν η γραμματοσειρά πηγής δεν βρεθεί. Γράφει [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::SaveOptions::set_DefaultRegularFont(System::String value) override
```

## Σχόλια



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

## Δείτε επίσης

* Κατηγορία [String](../../../system/string/)
* Κατηγορία [SaveOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)