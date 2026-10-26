---
title: InsertColumnAfter()
second_title: Aspose.Slides για C++ Αναφορά API
description: Εισάγετε μια νέα στήλη μετά από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null.
type: docs
weight: 339
url: /el/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) μέθοδος

Εισάγετε μια νέα στήλη μετά από αυτήν που έχει προσδιοριστεί. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
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

* Κλάση [MathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)