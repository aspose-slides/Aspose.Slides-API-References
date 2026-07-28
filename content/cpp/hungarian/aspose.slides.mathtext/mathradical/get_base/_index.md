---
title: get_Base()
second_title: Aspose.Slides C++ API hivatkozás
description: Base argumentum
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathradical/get_base/
---
## MathRadical::get_Base() metódus


Base argumentum

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRadical::get_Base() override
```

## Megjegyzések


Példa: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
auto baseElem = radical->get_Base();
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathRadical](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)