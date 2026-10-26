---
title: get_Limit()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: सीमा तर्क
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/mathlimit/get_limit/
---
## MathLimit::get_Limit() विधि


सीमा तर्क

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathLimit::get_Limit() override
```

## टिप्पणी


उदाहरण: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathLimit](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)