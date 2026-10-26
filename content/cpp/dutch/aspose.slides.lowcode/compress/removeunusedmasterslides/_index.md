---
title: RemoveUnusedMasterSlides()
second_title: Aspose.Slides voor C++ API-referentie
description: Voert compressie uit van de Presentation door ongebruikte masterdia's te verwijderen.
type: docs
weight: 1
url: /nl/aspose.slides.lowcode/compress/removeunusedmasterslides/
---
## Compress::RemoveUnusedMasterSlides(System::SharedPtr\<Presentation\>) methode

Voert compressie uit van de [Presentation](../../../aspose.slides/presentation/) door ongebruikte masterdia's te verwijderen.

```cpp
static void Aspose::Slides::LowCode::Compress::RemoveUnusedMasterSlides(System::SharedPtr<Presentation> pres)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | De presentatie-instantie |

## Opmerkingen




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
LowCode::Compress::RemoveUnusedMasterSlides(pres);
pres->Save(u"pres-out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [Compress](../)
* Naamruimte [Aspose::Slides::LowCode](../../)
* Bibliotheek [Aspose.Slides](../../../)