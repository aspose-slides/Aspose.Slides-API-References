---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि निर्दिष्ट करता है। जब true हो, तो डेलिमिटर ऊर्ध्वादर रूप से उसके ऑपरेण्ड की ऊँचाई से मेल खाने के लिए बढ़ता है। डिफ़ॉल्ट मान true है।
type: docs
weight: 105
url: /hi/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) विधि

BeginningCharacter, SeparatorCharacter, EndingCharacter की वृद्धि निर्दिष्ट करता है। जब true हो, तो डेलिमिटर ऊर्ध्वाधर रूप से उसके ऑपरेण्ड की ऊँचाई से मेल खाने के लिए बढ़ता है। डिफ़ॉल्ट मान true है।

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## सम्बंधित देखें

* क्लास [IMathDelimiter](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)