---
title: AddGroupShape()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuwe lege groepsvorm en voegt deze toe aan het einde van de vormverzameling. Het frame van de groep wordt automatisch aangepast om alle toegevoegde vormen te bevatten.
type: docs
weight: 352
url: /nl/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() methode


Creëert een nieuwe lege groepsvorm en voegt deze toe aan het einde van de vormverzameling. Het frame van de groep wordt automatisch aangepast om alle toegevoegde vormen te bevatten.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```


### Retourwaarde

Het nieuw aangemaakte [IGroupShape](../../igroupshape/).

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) methode


Creëert een nieuwe groepsvorm, zet de opgegeven SVG-afbeelding om in afzonderlijke vormen, en voegt de resulterende groep toe aan het einde van de vormverzameling.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | De [ISvgImage](../../isvgimage/) die vectorinhoud bevat om om te zetten in vormen. |
| x | **float** | De x-coördinaat van het frame van de groep, in punten. |
| y | **float** | De y-coördinaat van het frame van de groep, in punten. |
| width | **float** | De breedte van het frame van de groep, in punten. |
| height | **float** | De hoogte van het frame van de groep, in punten. |

### Retourwaarde

Het nieuw aangemaakte [IGroupShape](../../igroupshape/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IGroupShape](../../igroupshape/)
* Klasse [IShapeCollection](../)
* Klasse [ISvgImage](../../isvgimage/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)