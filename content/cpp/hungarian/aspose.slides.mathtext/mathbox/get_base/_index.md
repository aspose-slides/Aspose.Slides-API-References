---
title: get_Base()
second_title: Aspose.Slides C++ API referenciája
description: Base argumentum
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathbox/get_base/
---
## MathBox::get_Base() metódus


Base argumentum

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBox::get_Base() override
```

## Megjegyzés


Példa: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
auto baseArg = box->get_Base();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathBox](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)