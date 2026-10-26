---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ एपीआई संदर्भ
description: BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि निर्दिष्ट करता है। जब true हो, तो डिलीमीटर अपने ऑपरेन्ड की ऊँचाई से मेल खाने के लिए लंबवत बढ़ता है। डिफ़ॉल्ट मान true है।
type: docs
weight: 92
url: /hi/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() विधि

BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि निर्दिष्ट करता है। जब true हो, तो डिलीमीटर अपने ऑपरेन्ड की ऊँचाई से मेल खाने के लिए लंबवत बढ़ता है। डिफ़ॉल्ट मान true है।

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## टिप्पणियाँ

उदाहरण:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## देखें

* क्लास [IMathDelimiter](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)