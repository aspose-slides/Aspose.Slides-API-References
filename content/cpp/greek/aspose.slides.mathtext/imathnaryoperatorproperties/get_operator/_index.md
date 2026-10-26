---
title: get_Operator()
second_title: Aspose.Slides για την αναφορά API C++
description: "Χαρακτήρας Nary Operator Για παράδειγμα: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /el/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() μέθοδος

Χαρακτήρας Nary Operator Για παράδειγμα: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Δείτε επίσης

* Κλάση [IMathNaryOperatorProperties](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)