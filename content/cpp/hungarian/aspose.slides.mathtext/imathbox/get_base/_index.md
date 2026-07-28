---
title: get_Base()
second_title: Aspose.Slides C++ API referenciája
description: Base argumentum
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathbox/get_base/
---
## IMathBox::get_Base() metódus


Base argumentum

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBox::get_Base()=0
```

## Megjegyzések


Példa: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
auto baseArg = box->get_Base();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathBox](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)