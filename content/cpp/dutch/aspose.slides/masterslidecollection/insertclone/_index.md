---
title: InsertClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een kopie van een opgegeven master-slide toe op een opgegeven positie in de collectie. Gerelateerde lay-outslides worden ook gekopieerd.
type: docs
weight: 105
url: /nl/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) methode

Voegt een kopie van een opgegeven master-slide toe op een opgegeven positie in de collectie. Gerelateerde lay-outslides worden ook gekopieerd.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van nieuwe slide. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) om te klonen. |

### Retourwaarde

Ingevoegde master slide.

## Opmerkingen

Het volgende voorbeeld laat zien hoe je een master-slide kunt klonen in een andere PowerPoint [Presentation](../../presentation/). 
```cpp
// Maak een instantie van de Presentation-klasse om het bronpresentatiebestand te laden
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// Maak een instantie van de Presentation-klasse voor de doelpresentatie (waar de dia naartoe wordt gekloond)
auto destPres = System::MakeObject<Presentation>();

// Maak een instantie van ISlide uit de verzameling dia's in de bronpresentatie samen met
// Master-dia
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// Haal de master-dia's op van de doelpresentatie
auto masters = destPres->get_Masters();
// Kloon de gewenste master-dia van de bronpresentatie naar de collectie master-dia's in de
// Doelpresentatie
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// Collectie van dia's in de doelpresentatie
auto slides = destPres->get_Slides();
// Kloon de bron-dia naar de collectie van dia's in de doelpresentatie.
slides->AddClone(sourceSlide, iSlide, true);
// Sla de doelpresentatie op op schijf
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IMasterSlide](../../imasterslide/)
* Klasse [MasterSlideCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)