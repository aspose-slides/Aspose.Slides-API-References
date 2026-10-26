---
title: set_LimitLocation()
second_title: Aspose.Slides för C++ API-referens
description: Platsen för gränser (nedsänkt och upphöjd)
type: docs
weight: 40
url: /sv/aspose.slides.mathtext/imathnaryoperatorproperties/set_limitlocation/
---
## IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations) metod


Platsen för gränser (nedsänkt och upphöjd)

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_LimitLocation(MathLimitLocations value)=0
```

## Anmärkningar


Exempel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_LimitLocation(MathLimitLocations::SubscriptSuperscript);
```

## Se även

* Enum [MathLimitLocations](../../mathlimitlocations/)
* Klass [IMathNaryOperatorProperties](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)