---
title: get_Base()
second_title: Aspose.Slides C++ API Referencia
description: Alap argumentum
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() metódus


Alap argumentum

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## Megjegyzések


Példa: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // köbgyök
auto baseElem = radical->get_Base();
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathRadical](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)