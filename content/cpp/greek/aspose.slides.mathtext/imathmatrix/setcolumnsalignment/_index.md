---
title: SetColumnsAlignment()
second_title: Aspose.Slides για C++ API αναφορά
description: Ορίζει την οριζόντια στοίχιση των συγκεκριμένων στηλών
type: docs
weight: 261
url: /el/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) μέθοδος

Ορισμός της οριζόντιας στοίχισης των συγκεκριμένων στηλών

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | **int32_t** | Δείκτης μηδενικής βάσης της πρώτης στήλης για ορισμό της στοίχισης |
| columnsCount | **uint32_t** | Ο αριθμός των στηλών για τον καθορισμό της στοίχισης |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Νέα τιμή της οριζόντιας στοίχισης της συγκεκριμένης στήλης |
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Δείτε επίσης

* Απαρίθμηση [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Κλάση [IMathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)