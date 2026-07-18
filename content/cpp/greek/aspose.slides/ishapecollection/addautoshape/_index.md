---
title: AddAutoShape()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί ένα νέο αυτόματο σχήμα με προεπιλεγμένη μορφοποίηση και το προσθέτει στο τέλος της συλλογής σχημάτων.
type: docs
weight: 313
url: /el/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) μέθοδος

Δημιουργεί ένα νέο αυτόματο σχήμα με προεπιλεγμένη μορφοποίηση και το προσθέτει στο τέλος της συλλογής σχημάτων.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Το [ShapeType](../../shapetype/) του αυτόματου σχήματος που θα προστεθεί. |
| x | **float** | Η x-συντεταγμένη του shape\u2019s πλαισίου, σε μονάδες σημείων. |
| y | **float** | Η y-συντεταγμένη του shape\u2019s πλαισίου, σε μονάδες σημείων. |
| width | **float** | Το πλάτος του shape\u2019s πλαισίου, σε μονάδες σημείων. |
| height | **float** | Το ύψος του shape\u2019s πλαισίου, σε μονάδες σημείων. |

### Τιμή επιστροφής

Το νεοδημιουργημένο [IAutoShape](../../iautoshape/).

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) μέθοδος

Δημιουργεί ένα νέο αυτόματο σχήμα και το προσθέτει στο τέλος της συλλογής σχημάτων, προαιρετικά αρχικοποιώντας το με προεπιλεγμένη μορφοποίηση προτύπου.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Το [ShapeType](../../shapetype/) του αυτόματου σχήματος που θα προστεθεί. |
| x | **float** | Η x-συντεταγμένη του shape\u2019s πλαισίου, σε μονάδες σημείων. |
| y | **float** | Η y-συντεταγμένη του shape\u2019s πλαισίου, σε μονάδες σημείων. |
| width | **float** | Το πλάτος του shape\u2019s πλαισίου, σε μονάδες σημείων. |
| height | **float** | Το ύψος του shape\u2019s πλαισίου, σε μονάδες σημείων. |
| createFromTemplate | **bool** | Αληθές για την εφαρμογή προεπιλεγμένου στυλ προτύπου (απλό στυλ, κεντραρισμένο κείμενο και μη κενό όνομα) στο νέο σχήμα· ψευδές για τη δημιουργία του σχήματος με όλες τις ιδιότητες ορισμένες στις προεπιλεγμένες τιμές. |

### Τιμή επιστροφής

Το νεοδημιουργημένο [IAutoShape](../../iautoshape/).

## Δείτε επίσης

* Απαρίθμηση [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAutoShape](../../iautoshape/)
* Κλάση [IShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)