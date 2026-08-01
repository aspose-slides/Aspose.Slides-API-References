---
title: AddAutoShape()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuwe autoshape met standaardopmaak en voegt deze toe aan het einde van de vormencollectie.
type: docs
weight: 352
url: /nl/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) methode

Maakt een nieuwe autoshape met standaardopmaak en voegt deze toe aan het einde van de vormencollectie.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | De [ShapeType](../../shapetype/) van de toe te voegen autoshape. |
| x | **float** | De x-coördinaat van het frame van de vorm, in punten. |
| y | **float** | De y-coördinaat van het frame van de vorm, in punten. |
| width | **float** | De breedte van het frame van de vorm, in punten. |
| height | **float** | De hoogte van het frame van de vorm, in punten. |

### Retourwaarde

De nieuw aangemaakte [IAutoShape](../../iautoshape/).

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) methode

Maakt een nieuwe autoshape en voegt deze toe aan het einde van de vormencollectie, waarbij optioneel standaard sjabloonopmaak wordt toegepast.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | De [ShapeType](../../shapetype/) van de toe te voegen autoshape. |
| x | **float** | De x-coördinaat van het frame van de vorm, in punten. |
| y | **float** | De y-coördinaat van het frame van de vorm, in punten. |
| width | **float** | De breedte van het frame van de vorm, in punten. |
| height | **float** | De hoogte van het frame van de vorm, in punten. |
| createFromTemplate | **bool** | True om standaard sjabloonopmaak (eenvoudige stijl, gecentreerde tekst en een niet-lege naam) toe te passen op de nieuwe vorm; false om de vorm te maken met alle eigenschappen ingesteld op hun standaardwaarden. |

### Retourwaarde

De nieuw aangemaakte [IAutoShape](../../iautoshape/).

## Zie ook

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)