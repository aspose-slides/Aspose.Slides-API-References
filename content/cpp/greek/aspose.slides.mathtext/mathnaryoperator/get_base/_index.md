---
title: get_Base()
second_title: Aspose.Slides για C++ Αναφορά API
description: Παράμετρος Base
type: docs
weight: 1
url: /el/aspose.slides.mathtext/mathnaryoperator/get_base/
---
## MathNaryOperator::get_Base() μέθοδος

Base παράμετρος

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Base() override
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMathElement](../../imathelement/)
* Κλάση [MathNaryOperator](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)