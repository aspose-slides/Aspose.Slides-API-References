---
title: set_LimitLocation()
second_title: Referenční dokumentace API pro Aspose.Slides pro C++
description: Umístění limitů (dolní index a horní index)
type: docs
weight: 79
url: /cs/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) metoda

Umístění limitů (dolní index a horní index)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## Poznámky


Příklad: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Viz také

* Výčtový typ [MathLimitLocations](../../mathlimitlocations/)
* Třída [MathNaryOperator](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)