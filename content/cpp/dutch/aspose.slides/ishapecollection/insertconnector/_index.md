---
title: InsertConnector()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw connectorvorm en voegt deze in de vormverzameling in op de opgegeven index, met standaard sjabloonopmaak.
type: docs
weight: 391
url: /nl/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) method

Maakt een nieuw connectorvorm en voegt deze in de vormverzameling in op de opgegeven index, met standaard sjabloonopmaak.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop de connectorvorm moet worden ingevoegd. |
| shapeType | [ShapeType](../../shapetype/) | De [ShapeType](../../shapetype/) van de connectorvorm die moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het frame van de connector, in punten. |
| y | **float** | De y-coördinaat van het frame van de connector, in punten. |
| width | **float** | De breedte van het frame van de connector, in punten. |
| height | **float** | De hoogte van het frame van de connector, in punten. |

### Retourwaarde

De nieuw aangemaakte [IConnector](../../iconnector/).

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) method

Maakt een nieuw connectorvorm en voegt deze in de vormverzameling in op de opgegeven index, eventueel met standaard sjabloonopmaak.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop de connectorvorm moet worden ingevoegd. |
| shapeType | [ShapeType](../../shapetype/) | De [ShapeType](../../shapetype/) van de connectorvorm die moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het frame van de connector, in punten. |
| y | **float** | De y-coördinaat van het frame van de connector, in punten. |
| width | **float** | De breedte van het frame van de connector, in punten. |
| height | **float** | De hoogte van het frame van de connector, in punten. |
| createFromTemplate | **bool** | True om standaard sjabloonopmaak toe te passen (niet-lege naam, eenvoudige stijl); false om de connector te maken met standaard eigenschapswaarden. |

### Retourwaarde

De nieuw aangemaakte [IConnector](../../iconnector/).

## Zie ook

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)