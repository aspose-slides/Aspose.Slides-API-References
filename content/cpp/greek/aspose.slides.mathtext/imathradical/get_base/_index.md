---
title: get_Base()
second_title: Aspose.Slides για C++ Αναφορά API
description: Παράμετρος Base
type: docs
weight: 1
url: /el/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() μέθοδος


Παράμετρος Base

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // κυβική ρίζα
auto baseElem = radical->get_Base();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IMathRadical](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)