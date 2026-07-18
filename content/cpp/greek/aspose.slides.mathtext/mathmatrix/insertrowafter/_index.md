---
title: InsertRowAfter()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εισάγει μια νέα γραμμή μετά από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι κενά.
type: docs
weight: 300
url: /el/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) μέθοδος

Insert a new row after the specified one Initially all elements in the new row are null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rowIndex | **int32_t** | Δείκτης της γραμμής μετά την οποία θα εισαχθεί μια νέα |
## Παρατηρήσεις

Παράδειγμα:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Δείτε επίσης

* Κλάση [MathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)