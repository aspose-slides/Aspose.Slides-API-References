---
title: InsertColumnAfter()
second_title: Aspose.Slides για C++ Αναφορά API
description: Εισάγετε μια νέα στήλη μετά από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null.
type: docs
weight: 326
url: /el/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) μέθοδος

Εισάγετε μια νέα στήλη μετά τη συγκεκριμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | **int32_t** | Δείκτης της στήλης μετά την οποία θα εισαχθεί μια νέα |
## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Δείτε επίσης

* Κλάση [IMathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)