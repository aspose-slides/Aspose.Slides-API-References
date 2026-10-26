---
title: get_Name()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: फ़ंक्शन नाम उदाहरण के लिए, फ़ंक्शन नाम sin और cos हैं
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() मेथड


फ़ंक्शन नाम उदाहरण के लिए, फ़ंक्शन नाम sin और cos हैं

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## और देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathFunction](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)