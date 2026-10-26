---
title: AddConnector()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw connector-object met standaard-sjabloon-opmaak en voegt het toe aan het einde van de vormverzameling.
type: docs
weight: 378
url: /nl/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) method

Maakt een nieuw connector-object met de standaard-sjabloon-opmaak en voegt het toe aan het einde van de vormverzameling.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | De [ShapeType](../../shapetype/) van de connectorvorm om toe te voegen. |
| x | **float** | De x-coördinaat van het kader van de connector, in points. |
| y | **float** | De y-coördinaat van het kader van de connector, in points. |
| width | **float** | De breedte van het kader van de connector, in points. |
| height | **float** | De hoogte van het kader van de connector, in points. |

### Retourwaarde

De nieuw aangemaakte [IConnector](../../iconnector/).

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) method

Maakt een nieuw connector-object en voegt het toe aan het einde van de vormverzameling, met de mogelijkheid om standaard-sjabloon-opmaak toe te passen.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | De [ShapeType](../../shapetype/) van de connectorvorm om te maken. |
| x | **float** | De x-coördinaat van het kader van de connector, in points. |
| y | **float** | De y-coördinaat van het kader van de connector, in points. |
| width | **float** | De breedte van het kader van de connector, in points. |
| height | **float** | De hoogte van het kader van de connector, in points. |
| createFromTemplate | **bool** | True om standaard-sjabloon-opmaak toe te passen (niet-lege naam, eenvoudige stijl); false om de connector te maken met standaard-eigenschapswaarden. |

### Retourwaarde

De nieuw aangemaakte [IConnector](../../iconnector/).

## Zie ook

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)