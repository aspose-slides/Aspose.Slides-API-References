---
title: InsertConnector()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues connector shape und fügt es in die ShapeCollection an dem angegebenen Index ein, wobei die Standardvorlagenformatierung angewendet wird.
type: docs
weight: 430
url: /de/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) Methode

Erzeugt ein neues connector shape und fügt es in die ShapeCollection an dem angegebenen Index ein, wobei die Standardvorlagenformatierung angewendet wird.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem das connector shape eingefügt wird. |
| shapeType | [ShapeType](../../shapetype/) | Der [ShapeType](../../shapetype/) des einzufügenden connector shape. |
| x | **float** | Die x-Koordinate des connector\u2019s-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des connector\u2019s-Frames, in Punkten. |
| width | **float** | Die Breite des connector\u2019s-Frames, in Punkten. |
| height | **float** | Die Höhe des connector\u2019s-Frames, in Punkten. |

### Rückgabewert

Das neu erstellte [IConnector](../../iconnector/).

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) Methode

Erzeugt ein neues connector shape und fügt es in die ShapeCollection an dem angegebenen Index ein, wobei optional die Standardvorlagenformatierung angewendet wird.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem das connector shape eingefügt wird. |
| shapeType | [ShapeType](../../shapetype/) | Der [ShapeType](../../shapetype/) des einzufügenden connector shape. |
| x | **float** | Die x-Koordinate des connector\u2019s-Frames, in Punkten. |
| y | **float** | Die y-Koordinate des connector\u2019s-Frames, in Punkten. |
| width | **float** | Die Breite des connector\u2019s-Frames, in Punkten. |
| height | **float** | Die Höhe des connector\u2019s-Frames, in Punkten. |
| createFromTemplate | **bool** | True, um die Standardvorlagenformatierung anzuwenden (nicht leerer Name, einfacher Stil); false, um den connector mit den Standardwerte-Eigenschaften zu erstellen. |

### Rückgabewert

Das neu erstellte [IConnector](../../iconnector/).

## Siehe auch

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IConnector](../../iconnector/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)