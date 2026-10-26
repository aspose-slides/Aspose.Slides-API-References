---
title: Group()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके एक समूह में रखता है
type: docs
weight: 248
url: /hi/aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() विधि

इस तत्व को नीचे की कर्ली ब्रैकेट का उपयोग करके एक समूह में रखता है

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```

### रिटर्न वैल्यू

नया इंस्टेंस प्रकार [IMathGroupingCharacter](../../imathgroupingcharacter/) का

## टिप्पणियाँ



उदाहरण: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) विधि

इस तत्व को समूह में रखता है, एक समूहित अक्षर जैसे नीचे की कर्ली ब्रैकेट या अन्य का उपयोग करके

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| character | char16_t | समूहित अक्षर जैसे BOTTOM CURLY BRACKET (U+23DF) या कोई अन्य |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | समूहित अक्षर की स्थिति |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | समूह अक्षर का वर्टिकल जस्टिफिकेशन। यह ऑब्जेक्ट की बेसलाइन के संबंध में संरेखण निर्दिष्ट करता है। उदाहरण के लिए, जब समूह अक्षर ऑब्जेक्ट के ऊपर होता है, तो VerticalJustification के Top होने से ऑब्जेक्ट का शीर्ष बेसलाइन पर आ जाता है; जब VerticalJustification Bottom पर सेट होता है, तो ऑब्जेक्ट का निचला भाग बेसलाइन पर रहता है |

### रिटर्न वैल्यू

नया इंस्टेंस प्रकार [IMathGroupingCharacter](../../imathgroupingcharacter/) का

## टिप्पणियाँ



उदाहरण: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## देखें

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)