---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides för C++ API-referens
description: Operatörstecken växer vertikalt för att matcha operandens höjd
type: docs
weight: 66
url: /sv/aspose.slides.mathtext/imathnaryoperatorproperties/set_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool) metod


Operatortecken växer vertikalt för att matcha operandens höjd

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool value)=0
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