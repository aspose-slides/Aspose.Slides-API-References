---
title: CompressEmbeddedFonts()
second_title: Aspose.Slides voor C++ API Referentie
description: Voert compressie uit van de Presentation door ongebruikte tekens uit ingesloten lettertypen te verwijderen.
type: docs
weight: 27
url: /nl/aspose.slides.lowcode/compress/compressembeddedfonts/
---
## Compress::CompressEmbeddedFonts(System::SharedPtr\<Presentation\>) methode

Maakt compressie van de [Presentation](../../../aspose.slides/presentation/) door ongebruikte tekens uit ingesloten lettertypen te verwijderen.

```cpp
static void Aspose::Slides::LowCode::Compress::CompressEmbeddedFonts(System::SharedPtr<Presentation> pres)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | De presentatie-instantie |

## Opmerkingen




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::CompressEmbeddedFonts(pres);

pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [Compress](../)
* Namespace [Aspose::Slides::LowCode](../../)
* Bibliotheek [Aspose.Slides](../../../)