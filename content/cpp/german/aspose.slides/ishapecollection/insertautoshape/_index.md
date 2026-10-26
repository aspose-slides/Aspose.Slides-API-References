---
title: InsertAutoShape()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Autoform und fügt sie in die Formsammlung an dem angegebenen Index ein, wobei die Standardvorlagenformatierung angewendet wird.
type: docs
weight: 339
url: /de/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) Methode

Erstellt eine neue Autoform und fügt sie in die Formsammlung an dem angegebenen Index ein, wobei die Standardvorlagenformatierung angewendet wird.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem die neue Autoform eingefügt werden soll. |
| shapeType | [ShapeType](../../shapetype/) | Der [ShapeType](../../shapetype/) der einzufügenden Autoform. |
| x | **float** | Die x-Koordinate des Rahmens der Form, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der Form, in Punkten. |
| width | **float** | Die Breite des Rahmens der Form, in Punkten. |
| height | **float** | Die Höhe des Rahmens der Form, in Punkten. |

### Rückgabewert

Die neu erstellte [IAutoShape](../../iautoshape/).

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) Methode

Erstellt eine neue Autoform und fügt sie in die Formsammlung an dem angegebenen Index ein, wobei sie optional mit der Standardvorlagenformatierung initialisiert wird.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem die Autoform eingefügt werden soll. |
| shapeType | [ShapeType](../../shapetype/) | Der [ShapeType](../../shapetype/) der einzufügenden Autoform. |
| x | **float** | Die x-Koordinate des Rahmens der Form, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der Form, in Punkten. |
| width | **float** | Die Breite des Rahmens der Form, in Punkten. |
| height | **float** | Die Höhe des Rahmens der Form, in Punkten. |
| createFromTemplate | **bool** | True, um die Standardvorlagenformatierung anzuwenden (einschließlich eines nicht leeren Namens, einfachen Stils und zentriertem Text); false, um die Form mit allen Eigenschaften auf ihre Standardwerte zu setzen. |

### Rückgabewert

Die neu erstellte [IAutoShape](../../iautoshape/).

## Siehe auch

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)