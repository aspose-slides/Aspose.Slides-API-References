---
title: get_Base()
second_title: Aspose.Slides a C++ API referenciához
description: Base argumentum
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathlimit/get_base/
---
## IMathLimit::get_Base() metódus


Base argumentum

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Base()=0
```

## Megjegyzések


Példa: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathLimit](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)