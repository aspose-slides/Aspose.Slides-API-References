---
title: get_Base()
second_title: Aspose.Slides για την αναφορά API C++
description: Βασικό όρισμα
type: docs
weight: 1
url: /el/aspose.slides.mathtext/imathlimit/get_base/
---
## IMathLimit::get_Base() μέθοδος


Base ορίσμα

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Base()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## Δείτε επίσης

* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IMathLimit](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)