---
title: idx_get()
second_title: Aspose.Slides για την Αναφορά API C++
description: Στοιχεία του πίνακα
type: docs
weight: 209
url: /el/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) μέθοδος


Στοιχεία του πίνακα

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```


### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| row | **int32_t** | Ο δείκτης μηδενικής βάσης της γραμμής για λήψη του στοιχείου |
| column | **int32_t** | Ο δείκτης μηδενικής βάσης της στήλης για λήψη του στοιχείου |

### Τιμή Επιστροφής


## Σχόλια



Παράδειγμα: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IMathMatrix](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)