---
title: get_Operator()
second_title: Αναφορά API Aspose.Slides για C++
description: "Χαρακτήρας τελεστή Nary Για παράδειγμα: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /el/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() μέθοδος


Χαρακτήρας τελεστή Nary Για παράδειγμα: '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## Παρατηρήσεις


Παράδειγμα:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Δείτε επίσης

* Κλάση [MathNaryOperator](../)
* Ονοματοχώρος [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)