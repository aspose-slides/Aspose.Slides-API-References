---
title: set_LimitLocation()
second_title: Aspose.Slides för C++ API-referens
description: Placeringen av gränser (nedsänkt och upphöjt)
type: docs
weight: 79
url: /sv/aspose.slides.mathtext/mathnaryoperator/set_limitlocation/
---
## MathNaryOperator::set_LimitLocation(MathLimitLocations) metod

Placeringen av gränser (nedsänkt och upphöjt)

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_LimitLocation(MathLimitLocations value) override
```

## Anmärkningar


Exempel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Se även

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Klass [MathNaryOperator](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)