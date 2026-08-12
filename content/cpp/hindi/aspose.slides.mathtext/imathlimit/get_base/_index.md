---
title: get_Base()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: Base तर्क
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/imathlimit/get_base/
---
## IMathLimit::get_Base() मेथड


Base तर्क

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Base()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathLimit](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)