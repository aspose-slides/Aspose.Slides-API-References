---
title: set_LimitLocation()
second_title: Αναφορά API Aspose.Slides για C++
description: Η θέση των ορίων (δείκτης και εκθέτης)
type: docs
weight: 40
url: /el/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) μέθοδος

Η θέση των ορίων (δείκτης και εκθέτης)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
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