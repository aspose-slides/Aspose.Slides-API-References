---
title: get_Base()
second_title: Aspose.Slides for C++ API संदर्भ
description: Base तर्क
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/mathsubscriptelement/get_base/
---
## MathSubscriptElement::get_Base() मेथड


Base तर्क

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSubscriptElement::get_Base() override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto baseElem = subscriptElement->get_Base();
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathSubscriptElement](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)