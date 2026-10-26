---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides C++ API referenciája
description: Az operátor karakter függőlegesen nő, hogy megegyezzen az operandus magasságával
type: docs
weight: 53
url: /hu/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() metódus


Az operátor karakter függőlegesen nő, hogy megegyezzen az operandus magasságával

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
```

## Megjegyzések


Példa: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Lásd még

* Osztály [IMathNaryOperatorProperties](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)