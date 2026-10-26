---
title: get_DisableFontLigatures()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt een waarde op die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard is deze eigenschap ingesteld op false.
type: docs
weight: 183
url: /nl/aspose.slides.export/ihtmloptions/get_disablefontligatures/
---

## IHtmlOptions::get_DisableFontLigatures() methode

Haalt een waarde op die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op **true**, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard is deze eigenschap ingesteld op **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtmlOptions::get_DisableFontLigatures()=0
```

## Opmerkingen


Voorbeeld:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_DisableFontLigatures(true); // Schakel ligaturen uit in tekstweergave

pres->Save(outputSlidePath, SaveFormat::Html, options);
```

## Zie ook

* Klasse [IHtmlOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)