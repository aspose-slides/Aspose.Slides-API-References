---
title: InsertClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een kopie van een opgegeven layoutslide toe op de opgegeven positie van de collectie.
type: docs
weight: 14
url: /nl/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) methode


Voegt een kopie van een opgegeven layoutslide toe op de opgegeven positie van de collectie.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van de nieuwe slide. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) te klonen. |

### Retourwaarde

Ingevoegde slide.
## Opmerkingen



Nieuwe lay-out wordt gekoppeld aan de bovenliggende masterslide voor deze layoutslidescollectie. Dit is dus een analogie van kopiëren/plakken met de optie \"Use Destination Theme\" in PowerPoint. 

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [MasterLayoutSlideCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)