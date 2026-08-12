---
title: get_Limit()
second_title: Aspose.Slides for C++ API संदर्भ
description: सीमा तर्क
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imathlimit/get_limit/
---
## IMathLimit::get_Limit() मेथड


सीमा तर्क

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLimit::get_Limit()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"?\?\u001a?"));
auto limitArg = limitElement->get_Limit();
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathLimit](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)