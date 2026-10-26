---
title: get_Operator()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "Nary ऑपरेटर कैरेक्टर उदाहरण के लिए: '\\u2211', '\\u222B'"
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/imathnaryoperatorproperties/get_operator/
---
## IMathNaryOperatorProperties::get_Operator() मेथड


Nary ऑपरेटर कैरेक्टर उदाहरण के लिए: '\\u2211', '\\u222B'

```cpp
virtual char16_t Aspose::Slides::MathText::IMathNaryOperatorProperties::get_Operator()=0
```

## टिप्पणी


उदाहरण:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## देखें भी

* क्लास [IMathNaryOperatorProperties](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)