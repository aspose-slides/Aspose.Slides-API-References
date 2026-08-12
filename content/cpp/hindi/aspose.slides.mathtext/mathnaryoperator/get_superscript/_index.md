---
title: get_Superscript()
second_title: Aspose.Slides for C++ API संदर्भ
description: उदाहरण के लिए, समाकल के मामले में, एक supersript तर्क निर्दिष्ट करता है जो ऊपरी सीमा निर्धारित करता है
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() मेथड


एक supersript तर्क निर्दिष्ट करता है जो, उदाहरण के लिए, समाकल के मामले में, ऊपरी सीमा निर्धारित करता है।

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
```

## टिप्पणी


उदाहरण: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathNaryOperator](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)