---
title: AddClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een kopie van een opgegeven layoutdia toe aan het einde van de collectie.
type: docs
weight: 1
url: /nl/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) methode

Voegt een kopie van een opgegeven layoutdia toe aan het einde van de collectie.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) om te klonen. |

### Retourwaarde

Toegevoegde dia.

## Opmerkingen

1) Nieuwe indeling wordt gekoppeld aan de bovenliggende masterdia voor deze indelingsdia-collectie. Dus dit is een analogie van kopiëren/plakken met de optie "Use Destination Theme" in PowerPoint. 2) Analogie van deze methode is methode [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) toegankelijk via de eigenschap [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)