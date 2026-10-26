---
title: get_Base()
second_title: Aspose.Slides for C++ API referencia
description: Függvényargumentum
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() metódus

Függvényargumentum

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## Megjegyzés

Példa: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathFunction](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)