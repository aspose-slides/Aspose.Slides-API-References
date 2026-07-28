---
title: get_Superscript()
second_title: Aspose.Slides for C++ API referencia
description: Felső index argumentum
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_superscript/
---
## MathRightSubSuperscriptElement::get_Superscript() metódus


Felső index argumentum

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_Superscript() override
```

## Megjegyzés


Példa: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = subsuperscript->get_Superscript();
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMathElement](../../imathelement/)
* Osztály [MathRightSubSuperscriptElement](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)