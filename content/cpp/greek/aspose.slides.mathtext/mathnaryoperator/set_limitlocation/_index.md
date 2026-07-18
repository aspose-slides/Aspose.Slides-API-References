---
title: set_LimitLocation()
second_title: Αναφορά API του Aspose.Slides για C++
description: Η θέση των ορίων (δείκτης και εκθέτης)
type: docs
weight: 79
url: /el/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) μέθοδος


Η θέση των ορίων (δείκτης και εκθέτης)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Δείτε επίσης

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Κλάση [MathNaryOperator](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)