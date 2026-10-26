---
title: ToMathArray()
second_title: Αναφορά API Aspose.Slides για C++
description: Τοποθετεί σε έναν κατακόρυφο πίνακα
type: docs
weight: 183
url: /el/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() μέθοδος

Τοποθετεί σε έναν κατακόρυφο πίνακα

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```

### Τιμή Επιστροφής

Νέα παρουσία τύπου [IMathArray](../../imatharray/)
## Σχόλια

Παράδειγμα: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## Δείτε επίσης

* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathArray](../../imatharray/)
* Κλάση [IMathElement](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)