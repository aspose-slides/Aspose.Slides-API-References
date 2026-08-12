---
title: get_Superscript()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ऊपर लिपि
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/imathleftsubsuperscriptelement/get_superscript/
---
## IMathLeftSubSuperscriptElement::get_Superscript() method


ऊपर लिपि

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLeftSubSuperscriptElement::get_Superscript()=0
```

## टिप्पणी


उदाहरण:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = leftSubSuperscript->get_Superscript();
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathLeftSubSuperscriptElement](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)