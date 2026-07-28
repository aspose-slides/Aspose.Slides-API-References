---
title: get_Subscript()
second_title: Aspose.Slides C++ API Referencia
description: Alsó index argumentum
type: docs
weight: 1
url: /hu/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_subscript/
---
## MathRightSubSuperscriptElement::get_Subscript() metódus


Alsó index argumentum

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_Subscript() override
```

## Megjegyzések


Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = subsuperscript->get_Subscript();
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathRightSubSuperscriptElement](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)