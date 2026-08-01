---
title: set_DisableFontLigatures()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de gerenderde output. Standaard is deze eigenschap ingesteld op false.
type: docs
weight: 105
url: /nl/aspose.slides.export/htmloptions/set_disablefontligatures/
---
## HtmlOptions::set_DisableFontLigatures(bool) methode


Stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op **true**, worden ligaturen uitgeschakeld in de gerenderde output. Standaard is deze eigenschap ingesteld op **false**.

```cpp
void Aspose::Slides::Export::HtmlOptions::set_DisableFontLigatures(bool value) override
```

## Opmerkingen


Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Schakel ligaturen uit bij het renderen van tekst

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Zie ook

* Klasse [HtmlOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)