---
title: get_Base()
second_title: Αναφορά API του Aspose.Slides για C++
description: Παράμετρος Συνάρτησης
type: docs
weight: 14
url: /el/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() μέθοδος


Παράμετρος Συνάρτησης

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IMathFunction](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)