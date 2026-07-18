---
title: InsertRowBefore()
second_title: Αναφορά API Aspose.Slides για C++
description: Εισάγετε μια νέα γραμμή πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null.
type: docs
weight: 287
url: /el/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) μέθοδος

Εισάγετε μια νέα γραμμή πριν από αυτή που καθορίζεται. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rowIndex | **int32_t** | Δείκτης της γραμμής πριν από την οποία θα προστεθεί μια νέα |
## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Δείτε επίσης

* Κλάση [MathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)