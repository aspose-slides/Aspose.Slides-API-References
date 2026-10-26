---
title: get_DefaultRegularFont()
second_title: Aspose.Slides για την Αναφορά API του C++
description: "Επιστρέφει τη γραμματοσειρά που χρησιμοποιείται όταν δεν βρεθεί η πηγή γραμματοσειράς. Διαβάζει System::String."
type: docs
weight: 53
url: /el/aspose.slides.export/saveoptions/get_defaultregularfont/
---
## SaveOptions::get_DefaultRegularFont() μέθοδος

Επιστρέφει τη γραμματοσειρά που χρησιμοποιείται όταν δεν βρεθεί η πηγή γραμματοσειράς. Διαβάζει [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Export::SaveOptions::get_DefaultRegularFont() override
```

## Παρατηρήσεις



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

* Κλάση [String](../../../system/string/)
* Κλάση [SaveOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)