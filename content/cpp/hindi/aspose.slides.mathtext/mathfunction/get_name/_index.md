---
title: get_Name()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: फ़ंक्शन नाम। उदाहरण के लिए, फ़ंक्शन नाम sin और cos होते हैं।
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() विधि

फ़ंक्शन नाम। उदाहरण के लिए, फ़ंक्शन नाम sin और cos होते हैं।

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## टिप्पणी

उदाहरण:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathFunction](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)