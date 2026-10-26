---
title: AddAutoShape()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuwe auto vorm met standaardopmaak en voegt deze toe aan het einde van de vormverzameling.
type: docs
weight: 313
url: /nl/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) methode

Maakt een nieuwe auto-vorm met standaardopmaak en voegt deze toe aan het einde van de vormverzameling.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | De [ShapeType](../../shapetype/) van de auto-vorm die moet worden toegevoegd. |
| x | **float** | De x-coördinaat van het frame van de vorm, in punten. |
| y | **float** | De y-coördinaat van het frame van de vorm, in punten. |
| width | **float** | De breedte van het frame van de vorm, in punten. |
| height | **float** | De hoogte van het frame van de vorm, in punten. |

### Retourwaarde

De nieuw aangemaakte [IAutoShape](../../iautoshape/).

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) methode

Maakt een nieuwe auto-vorm en voegt deze toe aan het einde van de vormverzameling, waarbij optioneel de standaard sjabloonopmaak wordt toegepast.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | De [ShapeType](../../shapetype/) van de auto-vorm die moet worden toegevoegd. |
| x | **float** | De x-coördinaat van het frame van de vorm, in punten. |
| y | **float** | De y-coördinaat van het frame van de vorm, in punten. |
| width | **float** | De breedte van het frame van de vorm, in punten. |
| height | **float** | De hoogte van het frame van de vorm, in punten. |
| createFromTemplate | **bool** | True om de standaard sjabloonopmaak (eenvoudige stijl, gecentreerde tekst en een niet-lege naam) toe te passen op de nieuwe vorm; false om de vorm te maken waarbij alle eigenschappen op hun standaardwaarden zijn ingesteld. |

### Retourwaarde

De nieuw aangemaakte [IAutoShape](../../iautoshape/).

## Zie ook

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)