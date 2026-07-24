---
title: InsertConnector()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues Connector-Shape und fügt es in die Shape-Collection bei dem angegebenen Index ein, wobei die Standardvorlagenformatierung angewendet wird.
type: docs
weight: 391
url: /de/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) Methode

Erstellt ein neues Connector-Shape und fügt es in die Shape-Collection an der angegebenen Position ein, wobei die Standard-Vorlagenformatierung angewendet wird.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem das Connector-Shape eingefügt wird. |
| shapeType | [ShapeType](../../shapetype/) | Der [ShapeType](../../shapetype/) des einzufügenden Connector-Shapes. |
| x | **float** | Die x-Koordinate des Rahmens des Connectors, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens des Connectors, in Punkten. |
| width | **float** | Die Breite des Rahmens des Connectors, in Punkten. |
| height | **float** | Die Höhe des Rahmens des Connectors, in Punkten. |

### Rückgabewert

Das neu erstellte [IConnector](../../iconnector/).

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) Methode

Erstellt ein neues Connector-Shape und fügt es in die Shape-Collection an der angegebenen Position ein, wobei optional die Standard-Vorlagenformatierung angewendet wird.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem das Connector-Shape eingefügt wird. |
| shapeType | [ShapeType](../../shapetype/) | Der [ShapeType](../../shapetype/) des einzufügenden Connector-Shapes. |
| x | **float** | Die x-Koordinate des Rahmens des Connectors, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens des Connectors, in Punkten. |
| width | **float** | Die Breite des Rahmens des Connectors, in Punkten. |
| height | **float** | Die Höhe des Rahmens des Connectors, in Punkten. |
| createFromTemplate | **bool** | True, um die Standard-Vorlagenformatierung anzuwenden (nicht leerer Name, einfacher Stil); false, um den Connector mit Standard-Eigenschaftswerten zu erstellen. |

### Rückgabewert

Das neu erstellte [IConnector](../../iconnector/).

## Siehe auch

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)