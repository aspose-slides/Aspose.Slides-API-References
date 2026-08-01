---
title: set_DisableFontLigatures()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een waarde in die aangeeft of tekst wordt weergegeven zonder ligaturen te gebruiken. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de weergegeven output. Standaard is deze eigenschap ingesteld op false.
type: docs
weight: 339
url: /nl/aspose.slides.export/isvgoptions/set_disablefontligatures/
---
## ISSVGOptions::set_DisableFontLigatures(bool) methode

Stelt een waarde in die aangeeft of tekst wordt weergegeven zonder ligaturen te gebruiken. Wanneer ingesteld op **true**, worden ligaturen uitgeschakeld in de weergegeven output. Standaard is deze eigenschap ingesteld op **false**.

```cpp
virtual void Aspose::Slides::Export::ISVGOptions::set_DisableFontLigatures(bool value)=0
```

## Opmerkingen

Voorbeeld:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Schakel ligaturen uit bij het weergeven van tekst

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Zie ook

* Klasse [ISVGOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)