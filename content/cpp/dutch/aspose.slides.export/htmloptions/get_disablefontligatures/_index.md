---
title: get_DisableFontLigatures()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft een waarde die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de gerenderde output. Standaard is deze eigenschap ingesteld op false.
type: docs
weight: 92
url: /nl/aspose.slides.export/htmloptions/get_disablefontligatures/
---
## HtmlOptions::get_DisableFontLigatures() methode


Geeft een waarde die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op **true**, worden ligaturen uitgeschakeld in de gerenderde output. Standaard is deze eigenschap ingesteld op **false**.

```cpp
bool Aspose::Slides::Export::HtmlOptions::get_DisableFontLigatures() override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Ligaturen uitschakelen bij tekstweergave

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Zie ook

* Klasse [HtmlOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)