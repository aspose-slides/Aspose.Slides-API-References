---
title: get_Limit()
second_title: Aspose.Slides C++ API referenciája
description: Limit argumentum
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() metódus


Limit argumentum

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## Megjegyzések


Példa: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathLimit](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)