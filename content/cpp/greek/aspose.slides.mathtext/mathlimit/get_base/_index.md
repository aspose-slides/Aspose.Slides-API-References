---
title: get_Base()
second_title: Aspose.Slides για C++ API Αναφορά
description: Base παράμετρος
type: docs
weight: 1
url: /el/aspose.slides.mathtext/mathlimit/get_base/
---
## MathLimit::get_Base() μέθοδος


Base παράμετρος

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Base() override
```

## Σχόλια


Παράδειγμα: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathLimit](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)