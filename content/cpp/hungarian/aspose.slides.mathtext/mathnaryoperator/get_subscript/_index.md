---
title: get_Subscript()
second_title: Aspose.Slides C++ API hivatkozása
description: Megad egy alsó index argumentumot, amely például integrál esetén beállítja az alsó határt
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() metódus


Megad egy alsó index argumentumot, amely például integrál esetén beállítja az alsó határt

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
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
* Osztály [MathNaryOperator](../)
* Névtér [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)