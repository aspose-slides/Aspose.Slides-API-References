---
title: set_DefaultRegularFont()
second_title: Aspose.Slides C++ API hivatkozás
description: "Beállítja a betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található. Kiírja System::String."
type: docs
weight: 66
url: /hu/aspose.slides.export/isaveoptions/set_defaultregularfont/
---
## ISaveOptions::set_DefaultRegularFont(System::String) módszer

Beállítja a betűtípust, amelyet akkor használ, ha a forrás betűtípusa nem található. Kiírja [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_DefaultRegularFont(System::String value)=0
```

## Megjegyzések

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

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [ISaveOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)