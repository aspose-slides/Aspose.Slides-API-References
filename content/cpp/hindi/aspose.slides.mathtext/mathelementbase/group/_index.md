---
title: Group()
second_title: Aspose.Slides for C++ API संदर्भ
description: नीचे की कर्ली ब्रेस का उपयोग करके इस तत्व को एक समूह में रखता है
type: docs
weight: 235
url: /hi/aspose.slides.mathtext/mathelementbase/group/
---
## MathElementBase::Group() मेथड

इस तत्व को एक समूह में रखता है नीचे की कर्ली ब्रेस (curly bracket) का उपयोग करके

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group() override
```

### रिटर्न वैल्यू

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## टिप्पणियाँ



उदाहरण: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## MathElementBase::Group(char16_t, MathTopBotPositions, MathTopBotPositions) मेथड

इस तत्व को एक समूह में रखता है एक समूह वर्ण (grouping character) जैसे नीचे की कर्ली ब्रेस या अन्य का उपयोग करके

```cpp
System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::MathElementBase::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification) override
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| character | char16_t | Grouping Character such as BOTTOM CURLY BRACKET (U+23DF) or any other |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position of grouping character |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |

### रिटर्न वैल्यू

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## टिप्पणियाँ



उदाहरण: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', MathTopBotPositions::Bottom, MathTopBotPositions::Top);
```

## देखें भी

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)