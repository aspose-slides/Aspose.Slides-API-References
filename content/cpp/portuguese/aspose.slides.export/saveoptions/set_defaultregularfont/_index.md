---
title: set_DefaultRegularFont()
second_title: Referência da API Aspose.Slides para C++
description: "Define a fonte usada caso a fonte de origem não seja encontrada. Escreve System::String."
type: docs
weight: 66
url: /pt/aspose.slides.export/saveoptions/set_defaultregularfont/
---
## SaveOptions::set_DefaultRegularFont(System::String) método


Define a fonte usada caso a fonte de origem não seja encontrada. Escreve [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Export::SaveOptions::set_DefaultRegularFont(System::String value) override
```

## Observações



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

## Veja Também

* Classe [String](../../../system/string/)
* Classe [SaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)