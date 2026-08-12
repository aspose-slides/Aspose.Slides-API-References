---
title: get_VerticalJustification()
second_title: Aspose.Slides for C++ API संदर्भ
description: "समूह अक्षर का लंबवत संरेखण। वस्तु का बेसलाइन के सापेक्ष संरेखण निर्दिष्ट करता है। उदाहरण के लिए, जब समूह अक्षर वस्तु के ऊपर हो, तो Top का VerticalJustification यह दर्शाता है कि वस्तु का शीर्ष बेसलाइन पर आता है; जब VerticalJustification को Bottom पर सेट किया जाता है, तो वस्तु का निचला हिस्सा बेसलाइन पर होता है। डिफ़ॉल्ट: Position=Top के लिए Bottom, और Position=Bottom के लिए Top"
type: docs
weight: 66
url: /hi/aspose.slides.mathtext/imathgroupingcharacter/get_verticaljustification/
---
## IMathGroupingCharacter::get_VerticalJustification() विधि


समूह अक्षर का लंबवत संरेखण। ऑब्जेक्ट का बेसलाइन के सापेक्ष संरेखण निर्दिष्ट करता है। उदाहरण के तौर पर, जब समूह अक्षर ऑब्जेक्ट के ऊपर हो, तो Top का VerticalJustification यह दर्शाता है कि ऑब्जेक्ट का शीर्ष बेसलाइन पर आता है; जब VerticalJustification को Bottom पर सेट किया जाता है, तो ऑब्जेक्ट का निचला हिस्सा बेसलाइन पर होता है। डिफ़ॉल्ट: Position=Top के लिए Bottom, और Position=Bottom के लिए Top।

```cpp
virtual MathTopBotPositions Aspose::Slides::MathText::IMathGroupingCharacter::get_VerticalJustification()=0
```

## टिप्पणी


उदाहरण: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_VerticalJustification(MathTopBotPositions::Top);
```

## देखें

* एन्यूम [MathTopBotPositions](../../mathtopbotpositions/)
* क्लास [IMathGroupingCharacter](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)