---
title: get_Base()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: Base आर्ग्युमेंट
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/mathnaryoperator/get_base/
---
## MathNaryOperator::get_Base() विधि

Base आर्ग्युमेंट

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Base() override
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto baseArg = naryOperator->get_Base();
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathNaryOperator](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)