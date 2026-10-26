---
title: InsertPictureFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Bildrahmen, der das angegebene Bild enthält, und fügt ihn an dem angegebenen Index in die ShapeCollection ein.
type: docs
weight: 456
url: /de/aspose.slides/shapecollection/insertpictureframe/
---
## ShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) Methode

Erstellt einen neuen Bildrahmen, der das angegebene Bild enthält, und fügt ihn an dem angegebenen Index in die ShapeCollection ein.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem das Bildrahmen eingefügt wird. |
| shapeType | [ShapeType](../../shapetype/) | Gibt den in [ShapeType](../../shapetype/) enthaltenen Shape-Typ an, ausgenommen aller Arten von Linien:

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
| x | **float** | Die x-Koordinate des Bildrahmens, in Punkten. |
| y | **float** | Die y-Koordinate des Bildrahmens, in Punkten. |
| width | **float** | Die Breite des Bildrahmens, in Punkten. |
| height | **float** | Die Höhe des Bildrahmens, in Punkten. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Der [IPPImage](../../ippimage/) zur Anzeige im Bildrahmen. |

### Rückgabewert

Der neu erstellte [IPictureFrame](../../ipictureframe/).

## Siehe auch

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [ShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)