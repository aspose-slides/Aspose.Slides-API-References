---
title: set_Operator()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Χαρακτήρας Nary Operator Για παράδειγμα: '\\u2211', '\\u222B'"
type: docs
weight: 53
url: /el/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) μέθοδος

Χαρακτήρας Nary Operator Για παράδειγμα: '\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Δείτε επίσης

* Κλάση [MathNaryOperator](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)