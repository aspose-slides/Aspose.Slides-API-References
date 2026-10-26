---
title: get_Name()
second_title: Aspose.Slides για C++ API Αναφορά
description: Όνομα συνάρτησης Για παράδειγμα, τα ονόματα συνάρτησης είναι sin και cos
type: docs
weight: 1
url: /el/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() μέθοδος


Όνομα συνάρτησης Για παράδειγμα, τα ονόματα συνάρτησης είναι sin και cos

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathFunction](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)