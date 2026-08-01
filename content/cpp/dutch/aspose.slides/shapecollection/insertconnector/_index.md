---
title: InsertConnector()
second_title: Aspose.Slides voor C++ API Referentie
description: Creëert een nieuwe connectorvorm en voegt deze in de vormverzameling in op de opgegeven index, met toepassing van de standaard sjabloonopmaak.
type: docs
weight: 430
url: /nl/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) method

Maakt een nieuwe connectorvorm en voegt deze in de vormverzameling in op de opgegeven index, met toepassing van de standaard sjabloonopmaak.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop de connectorvorm moet worden ingevoegd. |
| shapeType | [ShapeType](../../shapetype/) | De [ShapeType](../../shapetype/) van de connectorvorm die moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het frame van de connector, in punten. |
| y | **float** | De y-coördinaat van het frame van de connector, in punten. |
| width | **float** | De breedte van het frame van de connector, in punten. |
| height | **float** | De hoogte van het frame van de connector, in punten. |

### Retourwaarde

De nieuw aangemaakte [IConnector](../../iconnector/).

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) method

Maakt een nieuwe connectorvorm en voegt deze in de vormverzameling in op de opgegeven index, waarbij optioneel de standaard sjabloonopmaak wordt toegepast.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | De nulgebaseerde index waarop de connectorvorm moet worden ingevoegd. |
| shapeType | [ShapeType](../../shapetype/) | De [ShapeType](../../shapetype/) van de connectorvorm die moet worden ingevoegd. |
| x | **float** | De x-coördinaat van het frame van de connector, in punten. |
| y | **float** | De y-coördinaat van het frame van de connector, in punten. |
| width | **float** | De breedte van het frame van de connector, in punten. |
| height | **float** | De hoogte van het frame van de connector, in punten. |
| createFromTemplate | **bool** | True om de standaard sjabloonopmaak toe te passen (naam niet leeg, eenvoudige stijl); false om de connector te maken met standaard eigenschapswaarden. |

### Retourwaarde

De nieuw aangemaakte [IConnector](../../iconnector/).

## Zie ook

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)