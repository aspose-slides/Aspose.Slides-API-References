---
title: InsertAutoShape()
second_title: Aspose.Slides για το C++ API Αναφορά
description: Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη, εφαρμόζοντας την προεπιλεγμένη μορφοποίηση προτύπου.
type: docs
weight: 339
url: /el/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) μέθοδος

Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σ shapes στο συγκεκριμένο δείκτη, εφαρμόζοντας την προεπιλεγμένη μορφοποίηση του προτύπου.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης που αρχίζει από το μηδέν όπου θα εισαχθεί το νέο αυτόματο σχήμα. |
| shapeType | [ShapeType](../../shapetype/) | Το [ShapeType](../../shapetype/) του αυτόματου σχήματος που θα εισαχθεί. |
| x | **float** | Η x-συντεταγμένη του πλαισίου του σχήματος, σε σημεία. |
| y | **float** | Η y-συντεταγμένη του πλαισίου του σχήματος, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου του σχήματος, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου του σχήματος, σε σημεία. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [IAutoShape](../../iautoshape/).

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) μέθοδος

Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σ shapes στο συγκεκριμένο δείκτη, προαιρετικά αρχικοποιώντας το με την προεπιλεγμένη μορφοποίηση του προτύπου.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης που αρχίζει από το μηδέν όπου θα εισαχθεί το αυτόματο σχήμα. |
| shapeType | [ShapeType](../../shapetype/) | Το [ShapeType](../../shapetype/) του αυτόματου σχήματος που θα εισαχθεί. |
| x | **float** | Η x-συντεταγμένη του πλαισίου του σχήματος, σε σημεία. |
| y | **float** | Η y-συντεταγμένη του πλαισίου του σχήματος, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου του σχήματος, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου του σχήματος, σε σημεία. |
| createFromTemplate | **bool** | True για να εφαρμοστεί η προεπιλεγμένη μορφοποίηση του προτύπου (συμπεριλαμβανομένου μη κενό ονόματος, απλής σχεδίασης και κεντρασμένου κειμένου); false για να δημιουργηθεί το σχήμα με όλες τις ιδιότητες στις προεπιλογές τους. |

### Τιμή Επιστροφής

Το νεοδημιουργημένο [IAutoShape](../../iautoshape/).

## Δείτε επίσης

* Απαρίθμηση [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAutoShape](../../iautoshape/)
* Κλάση [IShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)