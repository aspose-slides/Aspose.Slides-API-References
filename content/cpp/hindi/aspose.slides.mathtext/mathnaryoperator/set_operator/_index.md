---
title: set_Operator()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "Nary ऑपरेटर कैरेक्टर उदाहरण के लिए: '\\u2211', '\\u222B'"
type: docs
weight: 53
url: /hi/aspose.slides.mathtext/mathnaryoperator/set_operator/
---
## MathNaryOperator::set_Operator(char16_t) विधि


Nary ऑपरेटर कैरेक्टर उदाहरण के लिए: '\\u2211', '\\u222B'

```cpp
void Aspose::Slides::MathText::MathNaryOperator::set_Operator(char16_t value) override
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
char16_t operatorSymbol = naryOperator->get_Operator();
```

## देखें

* क्लास [MathNaryOperator](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* पुस्तकालय [Aspose.Slides](../../../)