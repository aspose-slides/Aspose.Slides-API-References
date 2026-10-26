---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि को निर्दिष्ट करता है। जब true हो, तो delimiters लंबवत बढ़ते हैं ताकि उनका operand ऊँचाई से मेल खाए। डिफ़ॉल्ट मान true है।
type: docs
weight: 92
url: /hi/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() विधि

BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि को निर्दिष्ट करता है। जब true हो, तो delimiters लंबवत बढ़ते हैं ताकि उनका operand ऊँचाई से मेल खाए। डिफ़ॉल्ट मान true है।

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## संबंधित देखें

* क्लास [MathDelimiter](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)