---
title: InsertAutoShape()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη, εφαρμόζοντας την προεπιλεγμένη μορφοποίηση προτύπου.
type: docs
weight: 378
url: /el/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) μέθοδος

Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη, εφαρμόζοντας την προεπιλεγμένη μορφοποίηση προτύπου.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το νέο αυτόματο σχήμα. |
| shapeType | [ShapeType](../../shapetype/) | Το [ShapeType](../../shapetype/) του αυτόματου σχήματος προς εισαγωγή. |
| x | **float** | Η συντεταγμένη x του πλαισίου του σχήματος, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πλαισίου του σχήματος, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου του σχήματος, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου του σχήματος, σε σημεία. |

### Τιμή Επιστροφής

Το πρόσφατα δημιουργημένο [IAutoShape](../../iautoshape/).

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) μέθοδος

Δημιουργεί ένα νέο αυτόματο σχήμα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη, προαιρετικά αρχικοποιώντας το με το προεπιλεγμένο στυλ προτύπου.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το αυτόματο σχήμα. |
| shapeType | [ShapeType](../../shapetype/) | Το [ShapeType](../../shapetype/) του αυτόματου σχήματος προς εισαγωγή. |
| x | **float** | Η συντεταγμένη x του πλαισίου του σχήματος, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πλαισίου του σχήματος, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου του σχήματος, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου του σχήματος, σε σημεία. |
| createFromTemplate | **bool** | Αληθές για να εφαρμοστεί η προεπιλεγμένη μορφοποίηση προτύπου (συμπεριλαμβανομένου ενός μη κενό ονόματος, απλού στυλ και κεντραρισμένου κειμένου); ψευδές για να δημιουργηθεί το σχήμα με όλες τις ιδιότητες ορισμένες στις προεπιλογές. |

### Τιμή Επιστροφής

Το πρόσφατα δημιουργημένο [IAutoShape](../../iautoshape/).

## Δείτε επίσης

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)