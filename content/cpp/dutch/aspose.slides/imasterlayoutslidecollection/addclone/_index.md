---
title: AddClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een kopie van een opgegeven layout-dia toe aan het einde van de collectie.
type: docs
weight: 1
url: /nl/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) methode

Voegt een kopie van een opgegeven layout-dia toe aan het einde van de collectie.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) te klonen. |

### Retourwaarde

Toegevoegde dia.

## Opmerkingen

1) Nieuwe lay-out wordt gekoppeld aan de bovenliggende master-dia voor deze lay-out-dia collectie. Dit is dus een equivalent van copy/paste met de optie "Use Destination Theme" in PowerPoint. 2) Een equivalent van deze methode is methode [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) toegankelijk via de eigenschap [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [IMasterLayoutSlideCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)