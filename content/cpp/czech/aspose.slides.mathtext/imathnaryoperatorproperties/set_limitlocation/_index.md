---
title: set_LimitLocation()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Umístění limitů (dolní a horní index)
type: docs
weight: 40
url: /cs/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) metoda


Umístění limitů (dolní a horní index)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
```

## Poznámky


Příklad: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Viz také

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Třída [IMathNaryOperatorProperties](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)