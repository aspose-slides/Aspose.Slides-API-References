---
title: idx_get()
second_title: Aspose.Slides για C++ Αναφορά API
description: Ανακτά το IMathElement στον καθορισμένο δείκτη.
type: docs
weight: 27
url: /el/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) μέθοδος

Λαμβάνει [IMathElement](../../imathelement/) στο συγκεκριμένο ευρετήριο.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| index | **int32_t** | Ο δείκτης του στοιχείου που αρχίζει από το μηδέν |

### Τιμή Επιστροφής

Το μαθηματικό στοιχείο.
## Σχόλια



Παράδειγμα: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathBlock](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)