---
title: get_VerticalJustification()
second_title: Aspose.Slides for C++ API संदर्भ
description: "समूह अक्षर का ऊर्ध्वधर संरेखण। बेसलाइन के सापेक्ष वस्तु की संरेखण को निर्दिष्ट करता है। उदाहरण के लिए, जब समूह अक्षर वस्तु के ऊपर होता है, तो Top की VerticalJustification दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर आता है; जब VerticalJustification को Bottom पर सेट किया जाता है, तो वस्तु का निचला भाग बेसलाइन पर रहता है। डिफ़ॉल्ट: Position=Top के लिए Bottom, और Position=Bottom के लिए Top"
type: docs
weight: 66
url: /hi/aspose.slides.mathtext/mathgroupingcharacter/get_verticaljustification/
---
## MathGroupingCharacter::get_VerticalJustification() मेथड

समूह अक्षर का ऊर्ध्वाधर संरेखण। बॉललाइन के सापेक्ष वस्तु की संरेखण को निर्दिष्ट करता है। उदाहरण के लिए, जब समूह अक्षर वस्तु के ऊपर हो, तो Top की VerticalJustification दर्शाता है कि वस्तु का शीर्ष बॉललाइन पर आता है; जब VerticalJustification को Bottom पर सेट किया जाता है, तो वस्तु का निचला भाग बॉललाइन पर रहता है। डिफ़ॉल्ट: Position=Top के लिए Bottom, और Position=Bottom के लिए Top

```cpp
MathTopBotPositions Aspose::Slides::MathText::MathGroupingCharacter::get_VerticalJustification() override
```

## टिप्पणी

उदाहरण: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## संबंधित देखें

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* क्लास [MathGroupingCharacter](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)