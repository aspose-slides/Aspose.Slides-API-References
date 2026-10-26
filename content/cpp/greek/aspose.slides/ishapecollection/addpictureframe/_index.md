---
title: AddPictureFrame()
second_title: Αναφορά API Aspose.Slides για C++
description: Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων.
type: docs
weight: 404
url: /el/aspose.slides/ishapecollection/addpictureframe/
---
## IShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Καθορίζει τον τύπο σχήματος που περιέχεται στο [ShapeType](../../shapetype/), εκτός από όλα τα είδη γραμμών:

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
| x | **float** | Η συντεταγμένη x του πλαισίου εικόνας, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πλαισίου εικόνας, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου εικόνας, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου εικόνας, σε σημεία. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Η [IPPImage](../../ippimage/) που θα εμφανιστεί στο πλαίσιο εικόνας. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [IPictureFrame](../../ipictureframe/).

## Δείτε επίσης

* Απαρίθμηση [ShapeType](../../shapetype/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPictureFrame](../../ipictureframe/)
* Κλάση [IPPImage](../../ippimage/)
* Κλάση [IShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)