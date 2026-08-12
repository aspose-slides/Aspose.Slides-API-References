---
title: get_GrowToMatchOperandHeight()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: ऑपरेटर कैरेक्टर ऊर्ध्वाधर रूप से बढ़ता है ताकि वह अपने ऑपरेण्ड की ऊँचाई से मेल खाए
type: docs
weight: 92
url: /hi/aspose.slides.mathtext/mathnaryoperator/get_growtomatchoperandheight/
---
## MathNaryOperator::get_GrowToMatchOperandHeight() विधि

ऑपरेटर कैरेक्टर ऊर्ध्वाधर रूप से बढ़ता है ताकि वह अपने ऑपरेन्ड की ऊँचाई से मेल खाए

```cpp
bool Aspose::Slides::MathText::MathNaryOperator::get_GrowToMatchOperandHeight() override
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## देखें

* क्लास [MathNaryOperator](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)