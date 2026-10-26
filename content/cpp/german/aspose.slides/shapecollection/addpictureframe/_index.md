---
title: AddPictureFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Bildrahmen, der das angegebene Bild enthält, und fügt ihn am Ende der Formensammlung hinzu.
type: docs
weight: 443
url: /de/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) Methode

Erstellt einen neuen Bildrahmen, der das angegebene Bild enthält, und fügt ihn am Ende der Formensammlung hinzu.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Gibt den Formtyp an, der in [ShapeType](../../shapetype/) enthalten ist, mit Ausnahme aller Arten von Linien:

[ShapeType::Line](../../shapetype/),

[ShapeType::StraightConnector1](../../shapetype/),

[ShapeType::BentConnector2](../../shapetype/),

[ShapeType::BentConnector3](../../shapetype/),

[ShapeType::BentConnector4](../../shapetype/),

[ShapeType::BentConnector5](../../shapetype/),

[ShapeType::CurvedConnector2](../../shapetype/),

[ShapeType::CurvedConnector3](../../shapetype/),

[ShapeType::CurvedConnector4](../../shapetype/),

[ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | Die x-Koordinate des Bildrahmens in Punkt. |
| y | **float** | Die y-Koordinate des Bildrahmens in Punkt. |
| width | **float** | Die Breite des Bildrahmens in Punkt. |
| height | **float** | Die Höhe des Bildrahmens in Punkt. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Das [IPPImage](../../ippimage/) zum Anzeigen im Bildrahmen. |

### Rückgabewert

Das neu erstellte [IPictureFrame](../../ipictureframe/).

## Siehe auch

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPictureFrame](../../ipictureframe/)
* Klasse [IPPImage](../../ippimage/)
* Klasse [ShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)