---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides för C++ API-referens
description: Operatörstecken växer vertikalt för att matcha operandens höjd
type: docs
weight: 92
url: /sv/aspose.slides.mathtext/mathnaryoperator/get_growtomatchoperandheight/
---
## MathNaryOperator::get_GrowToMatchOperandHeight() metod

Operatörstecknet växer vertikalt för att matcha operandens höjd

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_GrowToMatchOperandHeight() override
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