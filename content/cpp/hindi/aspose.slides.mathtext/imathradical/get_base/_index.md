---
title: get_Base()
second_title: Aspose.Slides for C++ API संदर्भ
description: Base तर्क
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/imathradical/get_base/
---
## IMathRadical::get_Base() मेथड

Base तर्क

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRadical::get_Base()=0
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // घन मूल
auto baseElem = radical->get_Base();
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathRadical](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)