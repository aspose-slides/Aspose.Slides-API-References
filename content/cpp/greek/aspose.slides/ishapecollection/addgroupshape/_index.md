---
title: AddGroupShape()
second_title: Αναφορά API Aspose.Slides για C++
description: Δημιουργεί ένα νέο κενό σχήμα ομάδας και το προσθέτει στο τέλος της συλλογής σχημάτων. Το πλαίσιο της ομάδας θα προσαρμοστεί αυτόματα ώστε να χωράει τυχόν σχήματα που προσαρτώνται σε αυτό.
type: docs
weight: 352
url: /el/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() μέθοδος

Δημιουργεί ένα νέο κενό σχήμα ομάδας και το προσθέτει στο τέλος της συλλογής σχημάτων. Το πλαίσιο της ομάδας θα προσαρμοστεί αυτόματα ώστε να χωράει τυχόν σχήματα που προσαρτώνται σε αυτό.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```

### Τιμή επιστροφής

Το νεοδημιουργημένο [IGroupShape](../../igroupshape/).

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) μέθοδος

Δημιουργεί ένα νέο σχήμα ομάδας, μετατρέπει την καθορισμένη εικόνα SVG σε επιμέρους σχήματα και προσθέτει την προκύπτουσα ομάδα στο τέλος της συλλογής σχημάτων.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | Η [ISvgImage](../../isvgimage/) που περιέχει διανυσματικό περιεχόμενο για μετατροπή σε σχήματα. |
| x | **float** | Η συντεταγμένη x του πλαισίου της ομάδας, σε σημεία. |
| y | **float** | Η συντεταγμένη y του πλαισίου της ομάδας, σε σημεία. |
| width | **float** | Το πλάτος του πλαισίου της ομάδας, σε σημεία. |
| height | **float** | Το ύψος του πλαισίου της ομάδας, σε σημεία. |

### Τιμή επιστροφής

Το νεοδημιουργημένο [IGroupShape](../../igroupshape/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IGroupShape](../../igroupshape/)
* Κλάση [IShapeCollection](../)
* Κλάση [ISvgImage](../../isvgimage/)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)