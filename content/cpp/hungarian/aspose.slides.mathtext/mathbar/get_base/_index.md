---
title: get_Base()
second_title: Aspose.Slides C++ API Referencia
description: Base argumentum
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathbar/get_base/
---
## MathBar::get_Base() metódus

Base argumentum
```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBar::get_Base() override
```

## Megjegyzések

Példa:
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathBar](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)