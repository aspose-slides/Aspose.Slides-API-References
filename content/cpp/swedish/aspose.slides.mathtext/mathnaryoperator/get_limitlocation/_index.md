---
title: get_LimitLocation()
second_title: Aspose.Slides för C++ API-referens
description: Platsen för gränser (nedre och övre index)
type: docs
weight: 66
url: /sv/aspose.slides.mathtext/mathnaryoperator/get_limitlocation/
---
## MathNaryOperator::get_LimitLocation() metod


Platsen för gränser (nedre och övre index)

```cpp
MathLimitLocations Aspose::Slides::MathText::MathNaryOperator::get_LimitLocation() override
```

## Anmärkningar


Exempel:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Se också

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Klass [MathNaryOperator](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)