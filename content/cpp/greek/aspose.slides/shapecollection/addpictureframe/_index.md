---
title: AddPictureFrame()
second_title: Aspose.Slides για την αναφορά API του C++
description: Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχήματος.
type: docs
weight: 443
url: /el/aspose.slides/shapecollection/addpictureframe/
---
## ShapeCollection::AddPictureFrame(ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το προσθέτει στο τέλος της συλλογής σχήματος.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::AddPictureFrame(ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
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
| x | **float** | Η συντεταγμένη x του πλαισίου εικόνας, σε μονάδες σημείου. |
| y | **float** | Η συντεταγμένη y του πλαισίου εικόνας, σε μονάδες σημείου. |
| width | **float** | Το πλάτος του πλαισίου εικόνας, σε μονάδες σημείου. |
| height | **float** | Το ύψος του πλαισίου εικόνας, σε μονάδες σημείου. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Το [IPPImage](../../ippimage/) που θα εμφανιστεί στο πλαίσιο εικόνας. |

### Τιμή επιστροφής

Το νεοδημιουργημένο [IPictureFrame](../../ipictureframe/).

## Δείτε επίσης

* Απαρίθμηση [ShapeType](../../shapetype/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPictureFrame](../../ipictureframe/)
* Κλάση [IPPImage](../../ippimage/)
* Κλάση [ShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)