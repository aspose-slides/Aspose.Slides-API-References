---
title: get_Base()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: Base तर्क
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/mathlimit/get_base/
---
## MathLimit::get_Base() मेथड


Base आर्ग्यूमेंट

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Base() override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto baseArg = limitElement->get_Base();
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathLimit](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)