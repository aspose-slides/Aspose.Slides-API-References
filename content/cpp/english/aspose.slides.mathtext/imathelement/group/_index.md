---
title: Group()
second_title: Aspose.Slides for C++ API Reference
description: Places this element in a group using a bottom curly bracket
type: docs
weight: 248
url: /aspose.slides.mathtext/imathelement/group/
---
## IMathElement::Group() method


Places this element in a group using a bottom curly bracket

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group()=0
```


### Return Value

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Remarks



Example: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group();
```

## IMathElement::Group(char16_t, MathTopBotPositions, MathTopBotPositions) method


Places this element in a group using a grouping character such as bottom curly bracket or another

```cpp
virtual System::SharedPtr<IMathGroupingCharacter> Aspose::Slides::MathText::IMathElement::Group(char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| character | char16_t | Grouping Character such as BOTTOM CURLY BRACKET (U+23DF) or any other |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position of grouping character |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Vertical justification of group character. Specifies the alignment of the object with respect to the baseline. For example, when the group character is above the object, VerticalJustification of Top signifies that the top of the object falls on the baseline; when VerticalJustification is set to Bottom, the bottom of the object is on the baseline |

### Return Value

New instance of type [IMathGroupingCharacter](../../imathgroupingcharacter/)
## Remarks



Example: 
```cpp
auto groupingElement = System::MakeObject<MathematicalText>(u"x;y;z")->Group(u'\u23E1', Aspose::Slides::MathText::MathTopBotPositions::Bottom, Aspose::Slides::MathText::MathTopBotPositions::Top);
```

## See Also

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathGroupingCharacter](../../imathgroupingcharacter/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)