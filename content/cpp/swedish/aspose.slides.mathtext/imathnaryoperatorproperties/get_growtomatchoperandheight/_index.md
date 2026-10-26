---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides för C++ API-referens
description: Operator-tecknet växer vertikalt för att matcha operandens höjd
type: docs
weight: 53
url: /sv/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() metod


Operator Character växer vertikalt för att matcha operandens höjd

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
```

## Anmärkningar


Exempel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Se även

* Klass [IMathNaryOperatorProperties](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)