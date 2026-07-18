---
title: InsertRowBefore()
second_title: Αναφορά API Aspose.Slides για C++
description: Εισάγετε μια νέα σειρά πριν από τη συγκεκριμένη. Αρχικά όλα τα στοιχεία στη νέα σειρά είναι null.
type: docs
weight: 274
url: /el/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) μέθοδος


Εισάγετε μια νέα σειρά πριν από αυτήν που καθορίζεται. Αρχικά όλα τα στοιχεία στη νέα σειρά είναι null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rowIndex | **int32_t** | Δείκτης της σειράς πριν από την εισαγωγή μιας νέας |

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Δείτε επίσης

* Κλάση [IMathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)