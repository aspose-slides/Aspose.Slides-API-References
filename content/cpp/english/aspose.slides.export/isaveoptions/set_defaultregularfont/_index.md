---
title: set_DefaultRegularFont()
second_title: Aspose.Slides for C++ API Reference
description: "Sets font used in case source font is not found. Writes System::String."
type: docs
weight: 66
url: /aspose.slides.export/isaveoptions/set_defaultregularfont/
---
## ISaveOptions::set_DefaultRegularFont(System::String) method


Sets font used in case source font is not found. Writes [System::String](../../../system/string/).

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_DefaultRegularFont(System::String value)=0
```

## Remarks



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

## See Also

* Class [String](../../../system/string/)
* Class [ISaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)