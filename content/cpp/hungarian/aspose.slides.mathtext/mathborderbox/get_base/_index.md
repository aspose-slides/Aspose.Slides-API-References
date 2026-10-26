---
title: get_Base()
second_title: Aspose.Slides C++ API hivatkozás
description: Base argumentum
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathborderbox/get_base/
---
## MathBorderBox::get_Base() metódus


Base argumentum

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBorderBox::get_Base() override
```

## Megjegyzések


Példa: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = borderBox->get_Base();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathBorderBox](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)