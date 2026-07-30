---
title: get_LimitLocation()
second_title: Aspose.Slides pro C++ referenční příručku API
description: Umístění limit (dolní index a horní index)
type: docs
weight: 66
url: /cs/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() metoda

Umístění limit (dolní index a horní index)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## Poznámky

Příklad:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Viz také

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Třída [MathNaryOperator](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)