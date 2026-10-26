---
title: get_Base()
second_title: Aspose.Slides C++ API referencia
description: Függvény argumentuma
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() metódus

Függvény argumentuma

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## Megjegyzés

Példa:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* osztály [IMathElement](../../imathelement/)
* osztály [IMathFunction](../)
* névtér [Aspose::Slides::MathText](../../)
* könyvtár [Aspose.Slides](../../../)