---
title: InsertRowAfter()
second_title: Αναφορά API Aspose.Slides για C++
description: Εισάγετε μια νέα γραμμή μετά τη συγκεκριμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null.
type: docs
weight: 287
url: /el/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) μέθοδος


Εισάγετε μια νέα γραμμή μετά τη συγκεκριμένη. Αρχικά όλα τα στοιχεία στη νέα γραμμή είναι null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rowIndex | **int32_t** | Δείκτης της γραμμής μετά την οποία θα εισαχθεί μια νέα |
## Σχόλια



Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Δείτε επίσης

* Κλάση [IMathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)