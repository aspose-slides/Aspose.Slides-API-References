---
title: get_Operator()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "Nary ऑपरेटर अक्षर उदाहरण के लिए: '\\u2211', '\\u222B'"
type: docs
weight: 40
url: /hi/aspose.slides.mathtext/mathnaryoperator/get_operator/
---
## MathNaryOperator::get_Operator() विधि

Nary ऑपरेटर अक्षर उदाहरण के लिए: '\\u2211', '\\u222B'

```cpp
char16_t Aspose::Slides::MathText::MathNaryOperator::get_Operator() override
```

## टिप्पणी

उदाहरण:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## संबंधित देखें

* क्लास [MathNaryOperator](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)