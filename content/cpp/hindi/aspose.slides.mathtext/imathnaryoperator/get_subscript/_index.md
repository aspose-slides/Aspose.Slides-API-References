---
title: get_Subscript()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: एक सबस्क्रिप्ट तर्क निर्दिष्ट करता है जो, उदाहरण के लिए, समाकल के मामले में, निचली सीमा निर्धारित करता है
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imathnaryoperator/get_subscript/
---
## IMathNaryOperator::get_Subscript() विधि


एक सबस्क्रिप्ट तर्क निर्दिष्ट करता है जो, उदाहरण के लिए, समाकल के मामले में, निचली सीमा निर्धारित करता है

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Subscript()=0
```

## टिप्पणियाँ


उदाहरण:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathNaryOperator](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)