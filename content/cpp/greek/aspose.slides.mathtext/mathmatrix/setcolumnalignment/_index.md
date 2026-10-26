---
title: SetColumnAlignment()
second_title: Αναφορά API Aspose.Slides για C++
description: Ορίζει την οριζόντια στοίχιση της καθορισμένης στήλης
type: docs
weight: 261
url: /el/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) μέθοδος

Ορίζει την οριζόντια στοίχιση της καθορισμένης στήλης

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | **int32_t** | Δεικτης στήλης που αρχίζει από το μηδέν |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Νέα τιμή της οριζόντιας στοίχισης της καθορισμένης στήλης |
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Δείτε επίσης

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Κλάση [MathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)