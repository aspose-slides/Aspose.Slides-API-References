---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ऑपरेटर कैरेक्टर ऊर्ध्वाधर रूप से बढ़ता है ताकि उसके ऑपरेण्ड की ऊँचाई के साथ मेल खा सके
type: docs
weight: 53
url: /hi/aspose.slides.mathtext/imathnaryoperatorproperties/get_growtomatchoperandheight/
---
## IMathNaryOperatorProperties::get_GrowToMatchOperandHeight() विधि


ऑपरेटर कैरेक्टर ऊर्ध्वाधर रूप से बढ़ता है ताकि उसके ऑपरेण्ड की ऊँचाई के साथ मेल खा सके

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_GrowToMatchOperandHeight()=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_GrowToMatchOperandHeight(true);
```

## संबंधित देखें

* क्लास [IMathNaryOperatorProperties](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)