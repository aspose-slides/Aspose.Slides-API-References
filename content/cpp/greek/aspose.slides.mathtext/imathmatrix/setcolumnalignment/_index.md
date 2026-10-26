---
title: SetColumnAlignment()
second_title: Aspose.Slides για την αναφορά API C++
description: Ορίζει την οριζόντια στοίχιση της συγκεκριμένης στήλης
type: docs
weight: 248
url: /el/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) μέθοδος

Ορίστε την οριζόντια στοίχιση της καθορισμένης στήλης

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| columnIndex | **int32_t** | Δείκτης στήλης αρχής από το μηδέν |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Νέα τιμή οριζόντιας στοίχισης της καθορισμένης στήλης |
## Παρατηρήσεις



Παράδειγμα:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## Δείτε επίσης

* Απαριθμήσιμο [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Κλάση [IMathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)