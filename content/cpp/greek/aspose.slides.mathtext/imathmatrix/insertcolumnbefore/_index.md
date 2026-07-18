---
title: InsertColumnBefore()
second_title: Αναφορά API Aspose.Slides για C++
description: Εισάγετε μια νέα στήλη πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στη νέα στήλη είναι null.
type: docs
weight: 313
url: /el/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) μέθοδος


Εισάγετε μια νέα στήλη πριν από την καθορισμένη. Αρχικά όλα τα στοιχεία στην καινούρια στήλη είναι null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | **int32_t** | Δείκτης της στήλης πριν από την εισαγωγή μιας νέας |
## Σημειώσεις



Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Δείτε επίσης

* Κλάση [IMathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)