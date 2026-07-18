---
title: AddAutoShape()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί ένα νέο αυτόματο σχήμα με προεπιλεγμένη μορφοποίηση και το προσθέτει στο τέλος της συλλογής σχημάτων.
type: docs
weight: 352
url: /el/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) μέθοδος

Δημιουργεί ένα νέο αυτόματο σχήμα με προεπιλεγμένη μορφοποίηση και το προσθέτει στο τέλος της συλλογής σχήματος.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Το [ShapeType](../../shapetype/) του αυτόματου σχήματος προς προσθήκη. |
| x | **float** | Η x-συντεταγμένη του πλαισίου του σχήματος, σε πόντους. |
| y | **float** | Η y-συντεταγμένη του πλαισίου του σχήματος, σε πόντους. |
| width | **float** | Το πλάτος του πλαισίου του σχήματος, σε πόντους. |
| height | **float** | Το ύψος του πλαισίου του σχήματος, σε πόντους. |

### Τιμή επιστροφής

Το νεοδημιουργημένο [IAutoShape](../../iautoshape/).

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) μέθοδος

Δημιουργεί ένα νέο αυτόματο σχήμα και το προσθέτει στο τέλος της συλλογής σχήματος, προαιρετικά αρχικοποιώντας το με προεπιλεγμένη μορφοποίηση προτύπου.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | Το [ShapeType](../../shapetype/) του αυτόματου σχήματος προς προσθήκη. |
| x | **float** | Η x-συντεταγμένη του πλαισίου του σχήματος, σε πόντους. |
| y | **float** | Η y-συντεταγμένη του πλαισίου του σχήματος, σε πόντους. |
| width | **float** | Το πλάτος του πλαισίου του σχήματος, σε πόντους. |
| height | **float** | Το ύψος του πλαισίου του σχήματος, σε πόντους. |
| createFromTemplate | **bool** | True για την εφαρμογή προεπιλεγμένου στυλ προτύπου (απλό στυλ, κεντρωμένο κείμενο και μη κενό όνομα) στο νέο σχήμα· false για τη δημιουργία του σχήματος με όλες τις ιδιότητες ορισμένες στις προεπιλεγμένες τιμές. |

### Τιμή επιστροφής

Το νεοδημιουργημένο [IAutoShape](../../iautoshape/).

## Δείτε επίσης

* Απαρίθμηση [ShapeType](../../shapetype/)
* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IAutoShape](../../iautoshape/)
* Κλάση [ShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)