---
title: get_LimitLocation()
second_title: Aspose.Slides για C++ Αναφορά API
description: Η θέση των ορίων (δείκτης και εκθέτης)
type: docs
weight: 27
url: /el/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() μέθοδος

Η θέση των ορίων (δείκτης και εκθέτης)

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## Παρατηρήσεις


Παράδειγμα:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Δείτε επίσης

* Απαρίθμηση [MathLimitLocations](../../mathlimitlocations/)
* Κλάση [IMathNaryOperatorProperties](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)