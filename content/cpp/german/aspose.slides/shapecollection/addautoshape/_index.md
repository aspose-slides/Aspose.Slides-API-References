---
title: AddAutoShape()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein neues AutoShape mit Standardformatierung und fügt es am Ende der ShapeCollection hinzu.
type: docs
weight: 352
url: /de/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) Methode

Erstellt ein neues AutoShape mit Standardformatierung und fügt es am Ende der ShapeCollection hinzu.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Der [ShapeType](../../shapetype/) des hinzuzufügenden AutoShapes. |
| x | **float** | Die x-Koordinate des Frames des Shapes, in Punkten. |
| y | **float** | Die y-Koordinate des Frames des Shapes, in Punkten. |
| width | **float** | Die Breite des Frames des Shapes, in Punkten. |
| height | **float** | Die Höhe des Frames des Shapes, in Punkten. |

### Rückgabewert

Das neu erstellte [IAutoShape](../../iautoshape/).

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) Methode

Erstellt ein neues AutoShape und fügt es am Ende der ShapeCollection hinzu, wobei optional die Standardvorlagenformatierung angewendet wird.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Der [ShapeType](../../shapetype/) des hinzuzufügenden AutoShapes. |
| x | **float** | Die x-Koordinate des Frames des Shapes, in Punkten. |
| y | **float** | Die y-Koordinate des Frames des Shapes, in Punkten. |
| width | **float** | Die Breite des Frames des Shapes, in Punkten. |
| height | **float** | Die Höhe des Frames des Shapes, in Punkten. |
| createFromTemplate | **bool** | True, um die Standardvorlagenformatierung (einfacher Stil, zentrierter Text und nicht leerer Name) auf das neue Shape anzuwenden; false, um das Shape mit allen Eigenschaften auf deren Standardwerte zu setzen. |

### Rückgabewert

Das neu erstellte [IAutoShape](../../iautoshape/).

## Siehe auch

* Aufzählung [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [ShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)