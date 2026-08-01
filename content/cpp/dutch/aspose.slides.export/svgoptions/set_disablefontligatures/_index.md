---
title: set_DisableFontLigatures()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op true, worden ligaturen uitgeschakeld in de gerenderde output. Standaard is deze eigenschap ingesteld op false.
type: docs
weight: 339
url: /nl/aspose.slides.export/svgoptions/set_disablefontligatures/
---
## SVGOptions::set_DisableFontLigatures(bool) methode

Stelt een waarde in die aangeeft of tekst wordt gerenderd zonder ligaturen te gebruiken. Wanneer ingesteld op **true**, worden ligaturen uitgeschakeld in de gerenderde output. Standaard is deze eigenschap ingesteld op **false**.

```cpp
void Aspose::Slides::Export::SVGOptions::set_DisableFontLigatures(bool value) override
```

## Opmerkingen

Voorbeeld: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<SVGOptions> options = System::MakeObject<SVGOptions>();
options->set_DisableFontLigatures(true); // Ligaturen uitschakelen bij tekstweergave

System::SharedPtr<System::IO::FileStream> fileStream = System::MakeObject<System::IO::FileStream>(u"slide-0.svg", System::IO::FileMode::Create, System::IO::FileAccess::Write);
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Zie ook

* Klasse [SVGOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)