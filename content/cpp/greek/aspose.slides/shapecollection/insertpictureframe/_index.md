---
title: InsertPictureFrame()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.
type: docs
weight: 456
url: /el/aspose.slides/shapecollection/insertpictureframe/
---
## ShapeCollection::InsertPictureFrame(int32_t, ShapeType, float, float, float, float, System::SharedPtr\<IPPImage\>) μέθοδος


Δημιουργεί ένα νέο πλαίσιο εικόνας που περιέχει την καθορισμένη εικόνα και το εισάγει στη συλλογή σχημάτων στη συγκεκριμένη θέση.

```cpp
System::SharedPtr<IPictureFrame> Aspose::Slides::ShapeCollection::InsertPictureFrame(int32_t index, ShapeType shapeType, float x, float y, float width, float height, System::SharedPtr<IPPImage> image) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το πλαίσιο εικόνας. |
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
| x | **float** | Η συντεταγμένη x του πλαισίου εικόνας, σε points. |
| y | **float** | Η συντεταγμένη y του πλαισίου εικόνας, σε points. |
| width | **float** | Το πλάτος του πλαισίου εικόνας, σε points. |
| height | **float** | Το ύψος του πλαισίου εικόνας, σε points. |
| image | [System::SharedPtr](../../../system/sharedptr/)\<[IPPImage](../../ippimage/)\> | Το [IPPImage](../../ippimage/) που θα εμφανιστεί στο πλαίσιο εικόνας. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [IPictureFrame](../../ipictureframe/).

## Δείτε επίσης

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPictureFrame](../../ipictureframe/)
* Class [IPPImage](../../ippimage/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)