---
title: GetColumnAlignment()
second_title: Aspose.Slides για C++ API Reference
description: Λαμβάνει την οριζόντια στοίχιση της καθορισμένης στήλης
type: docs
weight: 235
url: /el/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) μέθοδος

Λαμβάνει την οριζόντια στοίχιση της καθορισμένης στήλης

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | **int32_t** | Δείκτης στήλης με βάση το μηδέν |

### Τιμή επιστροφής

Οριζόντια στοίχιση της καθορισμένης στήλης
## Σχόλια



Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Δείτε επίσης

* Απαρίθμηση [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Κλάση [IMathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)