---
title: InsertAutoShape()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Autoform und fügt sie in die ShapeCollection an dem angegebenen Index ein, wobei die Standardvorlagenformatierung angewendet wird.
type: docs
weight: 378
url: /de/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) method

Erstellt eine neue Autoform und fügt sie in die ShapeCollection an dem angegebenen Index ein, wobei die Standardvorlagenformatierung angewendet wird.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem die neue Autoform eingefügt werden soll. |
| shapeType | [ShapeType](../../shapetype/) | Der [ShapeType](../../shapetype/) der einzufügenden Autoform. |
| x | **float** | Die x-Koordinate des shape\u2019s Rahmens, in Punkten. |
| y | **float** | Die y-Koordinate des shape\u2019s Rahmens, in Punkten. |
| width | **float** | Die Breite des shape\u2019s Rahmens, in Punkten. |
| height | **float** | Die Höhe des shape\u2019s Rahmens, in Punkten. |

### Return Value

Das neu erstellte [IAutoShape](../../iautoshape/).

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) method

Erstellt eine neue Autoform und fügt sie in die ShapeCollection an dem angegebenen Index ein, wobei sie optional mit der Standardvorlagenformatierung initialisiert wird.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem die Autoform eingefügt werden soll. |
| shapeType | [ShapeType](../../shapetype/) | Der [ShapeType](../../shapetype/) der einzufügenden Autoform. |
| x | **float** | Die x-Koordinate des shape\u2019s Rahmens, in Punkten. |
| y | **float** | Die y-Koordinate des shape\u2019s Rahmens, in Punkten. |
| width | **float** | Die Breite des shape\u2019s Rahmens, in Punkten. |
| height | **float** | Die Höhe des shape\u2019s Rahmens, in Punkten. |
| createFromTemplate | **bool** | True, um die Standardvorlagenformatierung anzuwenden (einschließlich eines nicht leeren Namens, eines einfachen Stils und zentrierten Texts); false, um die Form mit allen Eigenschaften auf ihre Standardwerte zu setzen. |

### Return Value

Das neu erstellte [IAutoShape](../../iautoshape/).

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)