---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides C++ API hivatkozás
description: Az operátor karakter függőlegesen nő, hogy megegyezzen az operandus magasságával
type: docs
weight: 92
url: /hu/aspose.slides.mathtext/mathnaryoperator/get_growtomatchoperandheight/
---
## MathNaryOperator::get_GrowToMatchOperandHeight() metódus


Az operátor karakter függőlegesen nő, hogy megegyezzen az operandus magasságával

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_GrowToMatchOperandHeight() override
```

## Megjegyzések


Példa: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Lásd még

* Osztály [MathNaryOperator](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)