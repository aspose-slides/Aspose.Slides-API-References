---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides C++ API referencia
description: Az operátor karakter függőlegesen növekszik, hogy megegyezzen az operandus magasságával
type: docs
weight: 66
url: /hu/aspose.slides.mathtext/imathnaryoperatorproperties/set_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool) metódus


Az operátor karakter függőlegesen növekszik, hogy megegyezzen az operandus magasságával

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool value)=0
```

## Megjegyzések


Példa: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## Lásd még

* Osztály [IMathNaryOperatorProperties](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)