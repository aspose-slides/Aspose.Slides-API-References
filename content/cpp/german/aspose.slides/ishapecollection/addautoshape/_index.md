---
title: AddAutoShape()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Autoform mit Standardformatierung und fügt sie am Ende der Formensammlung hinzu.
type: docs
weight: 313
url: /de/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) Methode

Erstellt eine neue Autoform mit der Standardformatierung und fügt sie am Ende der Formensammlung hinzu.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Das [ShapeType](../../shapetype/) der Autoform, die hinzugefügt werden soll. |
| x | **float** | Die x-Koordinate des Rahmens der Form, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der Form, in Punkten. |
| width | **float** | Die Breite des Rahmens der Form, in Punkten. |
| height | **float** | Die Höhe des Rahmens der Form, in Punkten. |

### Rückgabewert

Die neu erstellte [IAutoShape](../../iautoshape/).

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) Methode

Erstellt eine neue Autoform und fügt sie am Ende der Formensammlung hinzu, wobei optional die Standardvorlagenformatierung angewendet wird.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Das [ShapeType](../../shapetype/) der Autoform, die hinzugefügt werden soll. |
| x | **float** | Die x-Koordinate des Rahmens der Form, in Punkten. |
| y | **float** | Die y-Koordinate des Rahmens der Form, in Punkten. |
| width | **float** | Die Breite des Rahmens der Form, in Punkten. |
| height | **float** | Die Höhe des Rahmens der Form, in Punkten. |
| createFromTemplate | **bool** | True, um die Standardvorlagenformatierung (einfacher Stil, zentrierter Text und nicht-leerer Name) auf die neue Form anzuwenden; false, um die Form mit allen Eigenschaften auf deren Standardwerte zu erstellen. |

### Rückgabewert

Die neu erstellte [IAutoShape](../../iautoshape/).

## Siehe auch

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IAutoShape](../../iautoshape/)
* Klasse [IShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)