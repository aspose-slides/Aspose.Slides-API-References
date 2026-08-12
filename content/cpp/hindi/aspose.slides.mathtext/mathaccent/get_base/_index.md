---
title: get_Base()
second_title: Aspose.Slides for C++ API संदर्भ
description: वह तर्क जिसके ऊपर एक्सेंट लागू किया गया
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() मेथड

वह तर्क जिसके ऊपर एक्सेंट लागू किया गया

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
```

## टिप्पणी

उदाहरण: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathAccent](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)