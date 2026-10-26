---
title: get_Subscript()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक सबस्क्रिप्ट आर्ग्युमेंट निर्दिष्ट करता है जो, उदाहरण के लिए, इंटीग्रल के मामले में, निचली सीमा सेट करता है।
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() मेथड

सबस्क्रिप्ट आर्ग्युमेंट निर्दिष्ट करता है जो, उदाहरण के लिए, इंटीग्रल के मामले में, निचली सीमा सेट करता है।

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
```
## टिप्पणियाँ

उदाहरण: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathNaryOperator](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)