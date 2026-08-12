---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API संदर्भ
description: ऑपरेटर कैरेक्टर ऊर्ध्वाधर रूप से बढ़ता है ताकि उसके ऑपरेण्ड की ऊँचाई से मेल खा सके
type: docs
weight: 66
url: /hi/aspose.slides.mathtext/imathnaryoperatorproperties/set_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool) विधि


ऑपरेटर कैरेक्टर ऊर्ध्वाधर रूप से बढ़ता है ताकि उसके ऑपरेण्ड की ऊँचाई से मेल खा सके

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_GrowToMatchOperandHeight(bool value)=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## संबंधित देखें

* क्लास [IMathNaryOperatorProperties](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)