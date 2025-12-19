---
title: MathGroupingCharacter()
second_title: Aspose.Slides for C++ API Reference
description: Initializes a new instance of the MathGroupingCharacter class with the default grouping character U+23DF (BOTTOM CURLY BRACKET)
type: docs
weight: 92
url: /aspose.slides.mathtext/mathgroupingcharacter/mathgroupingcharacter/
---
## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>) constructor


Initializes a new instance of the [MathGroupingCharacter](../) class with the default grouping character U+23DF (BOTTOM CURLY BRACKET)

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The base element to which the bar is applied |
## Remarks



Example: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
```

## MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr\<IMathElement\>, char16_t, MathTopBotPositions, MathTopBotPositions) constructor


Initializes a new instance of the [MathGroupingCharacter](../) class.

```cpp
Aspose::Slides::MathText::MathGroupingCharacter::MathGroupingCharacter(System::SharedPtr<IMathElement> element, char16_t character, MathTopBotPositions position, MathTopBotPositions verticalJustification)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The base element to which the bar is applied |
| character | char16_t | Grouping Character |
| position | [MathTopBotPositions](../../mathtopbotpositions/) | Position of grouping character |
| verticalJustification | [MathTopBotPositions](../../mathtopbotpositions/) | Vertical justification of group character |
## Remarks



Example: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"), u'_', MathTopBotPositions::Top, MathTopBotPositions::Bottom);
```

## See Also

* Enum [MathTopBotPositions](../../mathtopbotpositions/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)