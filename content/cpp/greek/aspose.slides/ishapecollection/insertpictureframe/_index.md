---
title: InsertPictureFrame()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.
type: docs
weight: 417
url: /el/aspose.slides/ishapecollection/insertpictureframe/
---
## IShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) μέθοδος

Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στο καθορισμένο δείκτη.

```cpp
virtual System::SharedPtr<IPictureFrame> Aspose::Slides::IShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το πλαίσιο εικόνας. |
| shapeType | [ShapeType](../../shapetype/) | Καθορίζει τον τύπο σχήματος που περιέχεται στο [ShapeType](../../shapetype/), εκτός από όλους τους τύπους γραμμών:

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
| x | **float** | Η συντεταγμένη x του πλαισίου εικόνας, σε σημέια. |
| y | **float** | Η συντεταγμένη y του πλαισίου εικόνας, σε σημέια. |
| width | **float** | Το πλάτος του πλαισίου εικόνας, σε σημέια. |
| height | **float** | Το ύψος του πλαισίου εικόνας, σε σημέια. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Το [IPPImage](../../ippimage/) που θα εμφανιστεί στο πλαίσιο εικόνας. |

### Τιμή επιστροφής

Το νεοδημιουργημένο [IPictureFrame](../../ipictureframe/).

## Δείτε επίσης

* Απαρίθμηση [ShapeType](../../shapetype/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPictureFrame](../../ipictureframe/)
* Κλάση [IPPImage](../../ippimage/)
* Κλάση [IShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)