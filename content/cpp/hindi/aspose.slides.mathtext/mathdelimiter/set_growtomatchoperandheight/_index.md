---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API संदर्भ
description: BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि को निर्दिष्ट करता है। जब true हो, तो डिलीमीटर अपनी operand ऊँचाई से मेल खाने के लिए लंबवत रूप से बढ़ता है। डिफ़ॉल्ट मान true है
type: docs
weight: 105
url: /hi/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) विधि

BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि निर्दिष्ट करता है। जब true हो, तो डिलीमीटर अपने ऑपरेण्ड की ऊँचाई के अनुसार लंबवत रूप से बढ़ता है। डिफ़ॉल्ट मान true है

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## देखें

* क्लास [MathDelimiter](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)