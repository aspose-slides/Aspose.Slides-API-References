---
title: get_LimitLocation()
second_title: Aspose.Slides για την αναφορά API C++
description: Η θέση των ορίων (υποδείκτης και ανώδείκτης)
type: docs
weight: 66
url: /el/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() μέθοδος


Η θέση των ορίων (υποδείκτης και ανώδείκτης)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Δείτε επίσης

* Απαρίθμηση [MathLimitLocations](../../mathlimitlocations/)
* Κλάση [MathNaryOperator](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)