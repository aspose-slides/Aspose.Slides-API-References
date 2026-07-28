---
title: get_Base()
second_title: Aspose.Slides C++ API referenciája
description: Alap argumentum
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathphantom/get_base/
---
## IMathPhantom::get_Base() metódus


Base argumentum

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathPhantom::get_Base()=0
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
* Osztály [IMathPhantom](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)