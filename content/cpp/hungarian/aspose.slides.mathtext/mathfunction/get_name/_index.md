---
title: get_Name()
second_title: Aspose.Slides for C++ API referencia
description: Függvény neve Például a függvénynevek a sin és a cos
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() metódus


Függvény neve Például a függvénynevek a sin és a cos

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## Megjegyzések


Példa: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathFunction](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)