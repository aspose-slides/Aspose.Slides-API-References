---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides C++ API Referencia
description: Az operátor karakter függőlegesen nő, hogy megfeleljen operandusa magasságának
type: docs
weight: 105
url: /hu/aspose.slides.mathtext/mathnaryoperator/set_growtomatchoperandheight/
---
## MathNaryOperator::set_GrowToMatchOperandHeight(bool) metódus

Az operátor karakter függőlegesen nő, hogy megfeleljen operandusa magasságának

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_GrowToMatchOperandHeight(bool value) override
```

## Megjegyzések

Példa: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Lásd még

* Osztály [MathNaryOperator](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)