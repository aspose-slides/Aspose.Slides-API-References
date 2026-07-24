---
title: InsertPictureFrame()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen neuen Bildrahmen, der das angegebene Bild enthält, und fügt ihn an der angegebenen Position in die shape collection ein.
type: docs
weight: 417
url: /de/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) Methode

Erstellt einen neuen Bildrahmen, der das angegebene Bild enthält, und fügt ihn an der angegebenen Position in die shape collection ein.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### Argumente

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Der nullbasierte Index, an dem der Bildrahmen eingefügt werden soll. |
| shapeType | [ShapeType](../../shapetype/) | Gibt den Formtyp an, der in [ShapeType](../../shapetype/) enthalten ist, außer für alle Arten von Linien: |
|  |  | [ShapeType::Line](../../shapetype/), |
|  |  | [ShapeType::StraightConnector1](../../shapetype/), |
|  |  | [ShapeType::BentConnector2](../../shapetype/), |
|  |  | [ShapeType::BentConnector3](../../shapetype/), |
|  |  | [ShapeType::BentConnector4](../../shapetype/), |
|  |  | [ShapeType::BentConnector5](../../shapetype/), |
|  |  | [ShapeType::CurvedConnector2](../../shapetype/), |
|  |  | [ShapeType::CurvedConnector3](../../shapetype/), |
|  |  | [ShapeType::CurvedConnector4](../../shapetype/), |
|  |  | [ShapeType::CurvedConnector5](../../shapetype/). |
| x | **float** | Die x-Koordinate des Bildrahmens in Punkten. |
| y | **float** | Die y-Koordinate des Bildrahmens in Punkten. |
| width | **float** | Die Breite des Bildrahmens in Punkten. |
| height | **float** | Die Höhe des Bildrahmens in Punkten. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Das [IPPImage](../../ippimage/) zur Anzeige im Bildrahmen. |

### Rückgabewert

Das neu erstellte [IPictureFrame](../../ipictureframe/).

## Siehe auch

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IPictureFrame](../../ipictureframe/)
* Klasse [IPPImage](../../ippimage/)
* Klasse [IShapeCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)