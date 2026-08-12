---
title: set_VerticalJustification()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: "समूह अक्षर का vertical justification। ऑब्जेक्ट के baseline के संबंध में संरेखण निर्दिष्ट करता है। उदाहरण के लिए, जब समूह अक्षर ऑब्जेक्ट के ऊपर होता है, Top का VerticalJustification दर्शाता है कि ऑब्जेक्ट का शीर्ष baseline पर पड़ता है; जब VerticalJustification को Bottom पर सेट किया जाता है, ऑब्जेक्ट का निचला भाग baseline पर होता है Default: Position=Top के लिए Bottom, और Position=Bottom के लिए Top"
type: docs
weight: 79
url: /hi/aspose.slides.mathtext/imathgroupingcharacter/set_verticaljustification/
---
## IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions) विधि


समूह अक्षर का vertical justification। ऑब्जेक्ट की baseline के संबंध में संरेखण निर्दिष्ट करता है। उदाहरण के लिए, जब समूह अक्षर ऑब्जेक्ट के ऊपर होता है, Top का VerticalJustification दर्शाता है कि ऑब्जेक्ट का शीर्ष baseline पर आता है; जब VerticalJustification को Bottom पर सेट किया जाता है, तब ऑब्जेक्ट का निचला भाग baseline पर होता है। डिफ़ॉल्ट: Position=Top के लिए Bottom, और Position=Bottom के लिए Top

```cpp
virtual void Aspose::Slides::MathText::IMathGroupingCharacter::set_VerticalJustification(MathTopBotPositions value)=0
```

## टिप्पणियाँ


उदाहरण: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## संबंधित देखें

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* क्लास [IMathGroupingCharacter](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)