---
title: InsertClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een kopie van een opgegeven layoutdia toe op een opgegeven positie in de collectie.
type: docs
weight: 14
url: /nl/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) methode

Voegt een kopie van een opgegeven layoutdia toe op een opgegeven positie in de verzameling.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumenten

| Parameter | Type | Omschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van de nieuwe dia. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) om te klonen. |

### Retourwaarde

Ingevoegde dia.

## Opmerkingen

De nieuwe lay-out wordt gekoppeld aan de bovenliggende masterslide voor deze lay-outdia-verzameling. Dit is dus analoog aan kopiëren/plakken met de optie \"Use Destination Theme\" in PowerPoint.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [IMasterLayoutSlideCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)