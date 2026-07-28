---
title: get_Base()
second_title: Aspose.Slides for C++ API Referencia
description: Az argumentum, amelyhez a hangsúly hozzá lett rendelve
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() metódus


Az argumentum, amelyhez a hangsúly hozzá lett rendelve

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
```

## Megjegyzések


Példa: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathAccent](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)