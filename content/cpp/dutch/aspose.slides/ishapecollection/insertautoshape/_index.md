---
title: InsertAutoShape()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw auto-shape en voegt dit toe aan de shape-collectie op de opgegeven index, waarbij de standaard-sjabloonopmaak wordt toegepast.
type: docs
weight: 339
url: /nl/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) methode


Maakt een nieuwe auto-vorm en voegt deze in de vormverzameling in op de opgegeven index, met de standaard sjabloonopmaak.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nul-gebaseerde index waarop de nieuwe auto-vorm moet worden ingevoegd. |
| shapeType | [ShapeType](../../shapetype/) | De [ShapeType](../../shapetype/) van de in te voegen auto-vorm. |
| x | **float** | De x-coördinaat van het frame van de vorm\\u2019s, in punten. |
| y | **float** | De y-coördinaat van het frame van de vorm\\u2019s, in punten. |
| width | **float** | De breedte van het frame van de vorm\\u2019s, in punten. |
| height | **float** | De hoogte van het frame van de vorm\\u2019s, in punten. |

### Retourwaarde

De nieuw aangemaakte [IAutoShape](../../iautoshape/).

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) methode


Maakt een nieuwe auto-vorm en voegt deze in de vormverzameling in op de opgegeven index, eventueel met de standaard sjabloonopmaak.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nul-gebaseerde index waarop de auto-vorm moet worden ingevoegd. |
| shapeType | [ShapeType](../../shapetype/) | De [ShapeType](../../shapetype/) van de in te voegen auto-vorm. |
| x | **float** | De x-coördinaat van het frame van de vorm\\u2019s, in punten. |
| y | **float** | De y-coördinaat van het frame van de vorm\\u2019s, in punten. |
| width | **float** | De breedte van het frame van de vorm\\u2019s, in punten. |
| height | **float** | De hoogte van het frame van de vorm\\u2019s, in punten. |
| createFromTemplate | **bool** | True om de standaard sjabloonopmaak toe te passen (inclusief een niet-lege naam, eenvoudige stijl en gecentreerde tekst); false om de vorm te maken met alle eigenschappen ingesteld op hun standaardwaarden. |

### Retourwaarde

De nieuw aangemaakte [IAutoShape](../../iautoshape/).

## Zie ook

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [IShapeCollection](../)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)