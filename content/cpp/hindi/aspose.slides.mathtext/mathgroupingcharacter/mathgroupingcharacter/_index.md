---
title: MathGroupingCharacter()
second_title: Aspose.Slides for C++ API संदर्भ
description: डिफ़ॉल्ट ग्रुपिंग कैरेक्टर U+23DF (BOTTOM CURLY BRACKET) के साथ MathGroupingCharacter क्लास का नया इंस्टेंस इनिशियलाइज़ करता है
type: docs
weight: 92
url: /hi/aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) कन्स्ट्रक्टर

डिफ़ॉल्ट ग्रुपिंग कैरेक्टर U+23DF (BOTTOM CURLY BRACKET) के साथ [MathGroupingCharacter](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | वह बेस एलिमेंट जिससे बार लागू किया जाता है |
## टिप्पणी



उदाहरण: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) कन्स्ट्रक्टर

[MathGroupingCharacter](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | वह बेस एलिमेंट जिससे बार लागू किया जाता है |
| character | char16_t | ग्रुपिंग कैरेक्टर |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | ग्रुपिंग कैरेक्टर की पोजीशन |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | ग्रुप कैरेक्टर की वर्टिकल जस्टिफिकेशन |
## टिप्पणी



उदाहरण: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## संबंधित देखें

* एन्युम [MathTopBotPositions](../../mathtopbotpositions/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [IMathElement](../../imathelement/)
* क्लास [MathGroupingCharacter](../)
* नामस्थान [Aspose::Slides::MathText](../../)
* लाइब्रेरी [Aspose.Slides](../../../)