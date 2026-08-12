---
title: get_Subscript()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सबस्क्रिप्ट
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imathleftsubsuperscriptelement/get_subscript/
---
## IMathLeftSubSuperscriptElement::get_Subscript() मेथड

Subscript

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLeftSubSuperscriptElement::get_Subscript()=0
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = leftSubSuperscript->get_Subscript();
```

## संबंधित

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathLeftSubSuperscriptElement](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)