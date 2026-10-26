---
title: get_Base()
second_title: Aspose.Slides C++ API hivatkozás
description: Alap argumentum
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathnaryoperator/get_base/
---
## MathNaryOperator::get_Base() metódus

Base argumentum

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Base() override
```

## Megjegyzések

Példa:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathNaryOperator](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)