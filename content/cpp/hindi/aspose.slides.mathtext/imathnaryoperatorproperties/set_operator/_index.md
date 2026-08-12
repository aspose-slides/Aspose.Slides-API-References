---
title: set_Operator()
second_title: Aspose.Slides for C++ API संदर्भ
description: "Nary ऑपरेटर कैरेक्टर उदाहरण के लिए: '\\u2211', '\\u222B'"
type: docs
weight: 14
url: /hi/aspose.slides.mathtext/imathnaryoperatorproperties/set_operator/
---
## IMathNaryOperatorProperties::set_Operator(char16_t) विधि

Nary ऑपरेटर कैरेक्टर उदाहरण के लिए: '\\u2211', '\\u222B'

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_Operator(char16_t value)=0
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## संबंधित देखें

* क्लास [IMathNaryOperatorProperties](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)