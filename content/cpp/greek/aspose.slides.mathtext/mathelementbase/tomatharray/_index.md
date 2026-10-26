---
title: ToMathArray()
second_title: Αναφορά API Aspose.Slides για C++
description: Τοποθετεί σε έναν κατακόρυφο πίνακα
type: docs
weight: 170
url: /el/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() μέθοδος

Τοποθετεί σε έναν κατακόρυφο πίνακα

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```

### Τιμή Επιστροφής

Νέα παρουσία του τύπου [IMathArray](../../imatharray/)
## Παρατηρήσεις

Παράδειγμα:
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathArray](../../imatharray/)
* Κλάση [MathElementBase](../)
* Χώρος Ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)