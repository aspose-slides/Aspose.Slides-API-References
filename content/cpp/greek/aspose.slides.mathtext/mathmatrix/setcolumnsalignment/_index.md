---
title: SetColumnsAlignment()
second_title: Aspose.Slides για το C++ Αναφορά API
description: Ορίζει την οριζόντια στοίχιση των συγκεκριμένων στηλών
type: docs
weight: 274
url: /el/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) μέθοδος


Ορίστε την οριζόντια στοίχιση των συγκεκριμένων στηλών

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```


### Παράμετροι

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | Μηδενική βάση δείκτη της πρώτης στήλης για ορισμό της στοίχισης |
| columnsCount | **uint32_t** | Ο αριθμός των στηλών για τον καθορισμό της στοίχισης |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | Νέα τιμή της οριζόντιας στοίχισης της συγκεκριμένης στήλης |
## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## Δείτε επίσης

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Κλάση [MathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)