---
title: ToArray()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα.
type: docs
weight: 326
url: /el/aspose.slides/shapecollection/toarray/
---
## ShapeCollection::ToArray() μέθοδος


Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray() override
```


### Τιμή επιστροφής

Ένας πίνακας αντικειμένων [IShape](../../ishape/).

## ShapeCollection::ToArray(int32_t, int32_t) μέθοδος


Δημιουργεί και επιστρέφει έναν πίνακα που περιέχει όλα τα σχήματα στο καθορισμένο εύρος.

```cpp
System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::ShapeCollection::ToArray(int32_t startIndex, int32_t count) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | **int32_t** | Ο δείκτης του πρώτου σχήματος προς επιστροφή. |
| count | **int32_t** | Ο αριθμός των σχημάτων προς επιστροφή. |

### Τιμή επιστροφής

Ένας πίνακας αντικειμένων [IShape](../../ishape/).

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IShape](../../ishape/)
* Κλάση [ShapeCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)