---
title: get_Base()
second_title: Aspose.Slides C++ API Referencia
description: Base argumentum
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathlimit/get_base/
---
## MathLimit::get_Base() metódus


Base argumentum

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Base() override
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
* Osztály [MathLimit](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)