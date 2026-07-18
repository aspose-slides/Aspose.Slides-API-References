---
title: GetColumnAlignment()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει την οριζόντια στοίχιση της συγκεκριμένης στήλης
type: docs
weight: 248
url: /el/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) μέθοδος

Λαμβάνει την οριζόντια στοίχιση της συγκεκριμένης στήλης

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```

### Arguments

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | **int32_t** | Δείκτης στήλης που αρχίζει από το μηδέν |

### Return Value

Οριζόντια στοίχιση της συγκεκριμένης στήλης

## Remarks

Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## See Also

* Απαρίθμηση [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Κλάση [MathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)