---
title: get_Base()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: फ़ंक्शन तर्क
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() विधि


फ़ंक्शन तर्क

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## टिप्पणियाँ


उदाहरण:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## देखें भी

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathFunction](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)