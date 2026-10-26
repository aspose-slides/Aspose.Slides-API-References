---
title: get_Base()
second_title: Aspose.Slides for C++ API hivatkozás
description: Base argumentum
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/imathborderbox/get_base/
---
## IMathBorderBox::get_Base() metódus


Base argumentum

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBorderBox::get_Base()=0
```

## Megjegyzés


Példa: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
auto baseArg = borderBox->get_Base();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [IMathBorderBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)