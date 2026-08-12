---
title: get_Superscript()
second_title: Aspose.Slides for C++ API संदर्भ
description: ऊपरी लिपि
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imathsuperscriptelement/get_superscript/
---
## IMathSuperscriptElement::get_Superscript() विधि


ऊपरी लिपि

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSuperscriptElement::get_Superscript()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto superscript = System::MakeObject<MathematicalText>(u"i");
auto superscriptElement = System::MakeObject<MathSuperscriptElement>(baseElement, superscript);
auto super = superscriptElement->get_Superscript();
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathSuperscriptElement](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)