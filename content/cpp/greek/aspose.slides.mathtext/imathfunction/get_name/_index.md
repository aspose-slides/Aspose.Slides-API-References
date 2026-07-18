---
title: get_Name()
second_title: Aspose.Slides για C++ Αναφορά API
description: Όνομα συνάρτησης Για παράδειγμα, τα ονόματα συναρτήσεων είναι sin και cos
type: docs
weight: 1
url: /el/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() μέθοδος


Όνομα συνάρτησης Για παράδειγμα, τα ονόματα συναρτήσεων είναι sin και cos

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## Σχόλια


Παράδειγμα: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IMathFunction](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)