---
title: ToMathArray()
second_title: Aspose.Slides για C++ Αναφορά API
description: Τοποθετεί τα παιδικά στοιχεία σε έναν κάθετο πίνακα
type: docs
weight: 235
url: /el/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() μέθοδος


Τοποθετεί τα παιδικά στοιχεία σε έναν κάθετο πίνακα

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
```


### Τιμή Επιστροφής

Νέο αντικείμενο τύπου [IMathArray](../../imatharray/)
## Σχόλια



Παράδειγμα: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathArray](../../imatharray/)
* Κλάση [MathBlock](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)