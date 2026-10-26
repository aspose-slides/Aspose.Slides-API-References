---
title: CreateMathGroupingCharacter()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक गणितीय समूह अक्षर बनाता है
type: docs
weight: 1
url: /hi/aspose.slides.mathtext/imathgroupingcharacterfactory/createmathgroupingcharacter/
---
## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) मेथड

एक गणितीय समूह अक्षर बनाता है

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | समूह अक्षर लागू करने के लिए गणितीय तत्व |
| character | char16_t | समूह अक्षर |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | समूह अक्षर की स्थिति |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | ऊर्ध्वाधर समायोजन |

### रिटर्न मान

नया समूह अक्षर तत्व

## IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr\<IMathElement\>) मेथड

एक गणितीय समूह अक्षर बनाता है

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathGroupingCharacterFactory::CreateMathGroupingCharacter(System::SharedPtr<IMathElement> element)=0
```


### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | समूह अक्षर लागू करने के लिए गणितीय तत्व |

### रिटर्न मान

नया समूह अक्षर तत्व

## देखें

* एन्यूम [MathTopBotPositions](../../mathtopbotpositions/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathGroupingCharacter](../../imathgroupingcharacter/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [IMathGroupingCharacterFactory](../)
* नेमस्पेस [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)