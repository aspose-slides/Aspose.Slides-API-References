---
title: get_Limit()
second_title: Aspose.Slides για C++ API Αναφορά
description: Όρισμα περιορισμού
type: docs
weight: 14
url: /el/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() μέθοδος

Όρισμα περιορισμού

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
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
* Κλάση [MathLimit](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)