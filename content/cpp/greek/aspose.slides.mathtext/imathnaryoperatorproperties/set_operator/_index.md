---
title: set_Operator()
second_title: Aspose.Slides για το API αναφοράς C++
description: "Χαρακτήρας Nary Operator Για παράδειγμα: '\\u2211', '\\u222B'"
type: docs
weight: 14
url: /el/aspose.slides.mathtext/imathnaryoperatorproperties/set_operator/
---
## IMathNaryOperatorProperties::set_Operator(char16_t) μέθοδος

Χαρακτήρας Nary Operator Για παράδειγμα: '\\u2211', '\\u222B'

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_Operator(char16_t value)=0
```

## Σχόλια

Παράδειγμα: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## Δείτε επίσης

* Κλάση [IMathNaryOperatorProperties](../)
* Χώρος ονομάτων [Aspose::Slides::MathText](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)