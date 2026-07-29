---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides för C++ API-referens
description: Operatortecken växer vertikalt för att matcha operandens höjd
type: docs
weight: 105
url: /sv/aspose.slides.mathtext/mathnaryoperator/set_growtomatchoperandheight/
---
## MathNaryOperator::set_GrowToMatchOperandHeight(bool) metod

Operatortecken växer vertikalt för att matcha operandens höjd

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_GrowToMatchOperandHeight(bool value) override
```

## Anmärkningar

Exempel: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Se även

* Klass [MathNaryOperator](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)