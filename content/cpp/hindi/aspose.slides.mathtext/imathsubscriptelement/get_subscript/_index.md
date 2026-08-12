---
title: get_Subscript()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: सबस्क्रिप्ट
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imathsubscriptelement/get_subscript/
---
## IMathSubscriptElement::get_Subscript() विधि


सबस्क्रिप्ट

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathSubscriptElement::get_Subscript()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto sub = subscriptElement->get_Subscript();
```

## देखें भी

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* वर्ग [IMathElement](../../imathelement/)
* वर्ग [IMathSubscriptElement](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)