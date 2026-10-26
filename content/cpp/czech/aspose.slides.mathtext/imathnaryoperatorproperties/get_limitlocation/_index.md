---
title: get_LimitLocation()
second_title: Aspose.Slides pro C++ API Reference
description: Umístění limit (dolní index a horní index)
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/imathnaryoperatorproperties/get_limitlocation/
---
## IMathNaryOperatorProperties::get_LimitLocation() metoda


Umístění limit (dolní index a horní index)

```cpp
virtual MathLimitLocations Aspose::Slides::MathText::IMathNaryOperatorProperties::get_LimitLocation()=0
```

## Poznámky


Příklad: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Viz také

* Výčet [MathLimitLocations](../../mathlimitlocations/)
* třída [IMathNaryOperatorProperties](../)
* jmenný prostor [Aspose::Slides::MathText](../../)
* knihovna [Aspose.Slides](../../../)