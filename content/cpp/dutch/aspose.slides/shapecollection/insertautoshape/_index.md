---
title: InsertAutoShape()
second_title: Aspose.Slides voor C++ API-referentie
description: Creëert een nieuw autoshape en voegt het toe aan de vormcollectie op de gespecificeerde index, met toepassing van de standaard sjabloonopmaak.
type: docs
weight: 378
url: /nl/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) methode


Maakt een nieuw autoshape en voegt het toe aan de vormcollectie op de gespecificeerde index, met toepassing van de standaard sjabloonopmaak.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop het nieuwe autoshape moet worden ingevoegd. |
| shapeType | [ShapeType](../../shapetype/) | De [ShapeType](../../shapetype/) van het autoshape dat moet worden ingevoegd. |
| x | **float** | De x-coördinate van de shape\\u2019s frame, in punten. |
| y | **float** | De y-coördinate van de shape\\u2019s frame, in punten. |
| width | **float** | De breedte van de shape\\u2019s frame, in punten. |
| height | **float** | De hoogte van de shape\\u2019s frame, in punten. |

### Retourwaarde

De nieuw aangemaakte [IAutoShape](../../iautoshape/).

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) methode


Maakt een nieuw autoshape en voegt het toe aan de vormcollectie op de gespecificeerde index, met de optie om het te initialiseren met de standaard sjabloonstijl.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop het autoshape moet worden ingevoegd. |
| shapeType | [ShapeType](../../shapetype/) | De [ShapeType](../../shapetype/) van het autoshape dat moet worden ingevoegd. |
| x | **float** | De x-coördinate van de shape\\u2019s frame, in punten. |
| y | **float** | De y-coördinate van de shape\\u2019s frame, in punten. |
| width | **float** | De breedte van de shape\\u2019s frame, in punten. |
| height | **float** | De hoogte van de shape\\u2019s frame, in punten. |
| createFromTemplate | **bool** | True om de standaard sjabloonstijl toe te passen (inclusief een niet-lege naam, een eenvoudige stijl en gecentreerde tekst); false om de shape te maken met alle eigenschappen ingesteld op hun standaardwaarden. |

### Retourwaarde

De nieuw aangemaakte [IAutoShape](../../iautoshape/).

## Zie ook

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)