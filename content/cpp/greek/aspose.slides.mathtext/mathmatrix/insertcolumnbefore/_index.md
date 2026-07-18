---
title: InsertColumnBefore()
second_title: Aspose.Slides για C++ API Αναφορά
description: Εισάγετε μια νέα στήλη πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null.
type: docs
weight: 326
url: /el/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) μέθοδος

Εισάγετε μια νέα στήλη πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | **int32_t** | Δείκτης της στήλης πριν από την οποία θα εισαχθεί μια νέα |

## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Δείτε επίσης

* Κλάση [MathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)