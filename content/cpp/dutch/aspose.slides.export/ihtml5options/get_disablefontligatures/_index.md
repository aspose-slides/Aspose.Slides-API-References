---
title: get_DisableFontLigatures()
second_title: Aspose.Slides voor C++ API-referentie
description: Geeft een waarde die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard is deze eigenschap ingesteld op false.
type: docs
weight: 131
url: /nl/aspose.slides.export/ihtml5options/get_disablefontligatures/
---
## IHtml5Options::get_DisableFontLigatures() methode

Geeft een waarde die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op **true**, worden ligaturen uitgeschakeld in de gerenderde uitvoer. Standaard is deze eigenschap ingesteld op **false**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_DisableFontLigatures()=0
```

## Opmerkingen

Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<Html5Options> options = System::MakeObject<Html5Options>();
options->set_DisableFontLigatures(true); // Schakel ligaturen uit bij het renderen van tekst

pres->Save(outputSlidePath, SaveFormat::Html5, options);
```

## Zie ook

* Klasse [IHtml5Options](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)