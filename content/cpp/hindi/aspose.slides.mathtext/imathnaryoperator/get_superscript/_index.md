---
title: get_Superscript()
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: एक सुपरस्क्रिप्ट तर्क निर्दिष्ट करता है जो, उदाहरण के लिए, इंटीग्रल के मामले में, ऊपरी सीमा सेट करता है
type: docs
weight: 27
url: /hi/aspose.slides.mathtext/imathnaryoperator/get_superscript/
---
## IMathNaryOperator::get_Superscript() मेथड

एक सुपरस्क्रिप्ट तर्क निर्दिष्ट करता है जो, उदाहरण के लिए, इंटीग्रल के मामले में, ऊपरी सीमा सेट करता है

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathNaryOperator::get_Superscript()=0
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathNaryOperator](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)