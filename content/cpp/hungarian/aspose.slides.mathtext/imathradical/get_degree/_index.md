---
title: get_Degree()
second_title: Aspose.Slides C++ API referenciája
description: Fok argumentum
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/imathradical/get_degree/
---
## IMathRadical::get_Degree() metódus


Fok argumentum

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Degree()=0
```

## Megjegyzések


Példa: 
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // köbgyök
auto degreeElem = radical->get_Degree();
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathRadical](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)