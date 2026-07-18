---
title: idx_get()
second_title: Aspose.Slides για C++ API Αναφορά
description: Στοιχείο του πίνακα
type: docs
weight: 209
url: /el/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) μέθοδος

Στοιχείο του πίνακα

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | **int32_t** | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη του στοιχείου |
| column | **int32_t** | Ο δείκτης μηδενικής βάσης της στήλης για λήψη του στοιχείου |

### Τιμή Επιστροφής


## Παρατηρήσεις



Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)