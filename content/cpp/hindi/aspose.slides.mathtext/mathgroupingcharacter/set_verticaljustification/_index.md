---
title: set_VerticalJustification()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "समूह अक्षर का लंबवत संरेखण। ऑब्जेक्ट को बेसलाइन के सापेक्ष संरेखित करने को निर्दिष्ट करता है। उदाहरण के लिए, जब समूह अक्षर ऑब्जेक्ट के ऊपर होता है, तो Top का VerticalJustification दर्शाता है कि ऑब्जेक्ट का शीर्ष बेसलाइन पर आता है; जब VerticalJustification Bottom पर सेट किया जाता है, तो ऑब्जेक्ट का निचला हिस्सा बेसलाइन पर रहता है। डिफ़ॉल्ट: Position=Top के लिए Bottom, और Position=Bottom के लिए Top"
type: docs
weight: 79
url: /hi/aspose.slides.mathtext/mathgroupingcharacter/set_verticaljustification/
---
## MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) विधि

समूह अक्षर का लंबवत संरेखण। ऑब्जेक्ट की बेसलाइन के सापेक्ष संरेखण को निर्दिष्ट करता है। उदाहरण के लिए, जब समूह अक्षर ऑब्जेक्ट के ऊपर होता है, तो Top का VerticalJustification दर्शाता है कि ऑब्जेक्ट का शीर्ष बेसलाइन पर आता है; जब VerticalJustification Bottom पर सेट किया जाता है, तो ऑब्जेक्ट का निचला हिस्सा बेसलाइन पर रहता है। डिफ़ॉल्ट: Position=Top के लिए Bottom, और Position=Bottom के लिए Top

```cpp
void Aspose::Slides::MathText::MathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value) override
```

## टिप्पणियाँ

उदाहरण: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## संबंधित देखें

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* क्लास [MathGroupingCharacter](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)