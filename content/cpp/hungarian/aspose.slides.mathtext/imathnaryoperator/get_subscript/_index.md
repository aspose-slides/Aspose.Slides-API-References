---
title: get_Subscript()
second_title: Aspose.Slides C++ API referencia
description: Megadja az alsó index argumentumot, amely például egy integrál esetén az alsó határt állítja be
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/imathnaryoperator/get_subscript/
---
## IMathNaryOperator::get_Subscript() metódus

Megadja az alsó index argumentumot, amely például egy integrál esetén az alsó határt állítja be

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Subscript()=0
```
## Megjegyzések

Példa: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```
## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathNaryOperator](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)