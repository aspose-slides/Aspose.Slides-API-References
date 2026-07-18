---
title: get_Limit()
second_title: Aspose.Slides για C++ Αναφορά API
description: Όρισμα ορίου
type: docs
weight: 14
url: /el/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() μέθοδος


Όρισμα ορίου

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [IMathLimit](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)