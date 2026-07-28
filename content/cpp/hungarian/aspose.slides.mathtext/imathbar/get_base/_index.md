---
title: get_Base()
second_title: Aspose.Slides C++ API referencia
description: Alap argumentum
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathbar/get_base/
---
## IMathBar::get_Base() metódus


Alap argumentum

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBar::get_Base()=0
```

## Megjegyzések


Példa: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [IMathBar](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)