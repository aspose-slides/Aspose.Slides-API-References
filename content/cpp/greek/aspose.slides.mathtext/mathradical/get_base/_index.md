---
title: get_Base()
second_title: Aspose.Slides για C++ API Αναφορά
description: Base παράμετρος
type: docs
weight: 1
url: /el/aspose.slides.mathtext/mathradical/get_base/
---
## MathRadical::get_Base() μέθοδος

Base παράμετρος

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Base() override
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto baseElem = radical->get_Base();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathRadical](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)