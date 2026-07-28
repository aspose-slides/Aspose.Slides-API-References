---
title: get_Subscript()
second_title: Aspose.Slides for C++ API referencia
description: Alsó index
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathleftsubsuperscriptelement/get_subscript/
---
## MathLeftSubSuperscriptElement::get_Subscript() metódus


Alsó index

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLeftSubSuperscriptElement::get_Subscript() override
```

## Megjegyzések


Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = leftSubSuperscript->get_Subscript();
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathLeftSubSuperscriptElement](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)