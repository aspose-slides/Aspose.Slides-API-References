---
title: get_Base()
second_title: Aspose.Slides for C++ API Referencia
description: Base argumentum
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathphantom/get_base/
---
## MathPhantom::get_Base() metódus


Base argumentum

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathPhantom::get_Base() override
```

## Megjegyzések


Példa: 
```cpp
System::SharedPtr<MathPhantom> mathBar = System::MakeObject<MathPhantom>(System::MakeObject<MathematicalText>(u"x"));
System::SharedPtr<IMathElement> baseElement = mathBar->get_Base();
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathPhantom](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)