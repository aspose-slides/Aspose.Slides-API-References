---
title: get_Superscript()
second_title: Aspose.Slides C++ API hivatkozás
description: Megad egy felső index argumentumot, amely például integrál esetén beállítja a felső határt
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() metódus


Megad egy felső index argumentumot, amely például integrál esetén beállítja a felső határt

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
```

## Megjegyzések


Példa:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathNaryOperator](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)