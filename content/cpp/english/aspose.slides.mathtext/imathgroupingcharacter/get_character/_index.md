---
title: get_Character()
second_title: Aspose.Slides for C++ API Reference
description: "Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET)"
type: docs
weight: 14
url: /aspose.slides.mathtext/imathgroupingcharacter/get_character/
---
## IMathGroupingCharacter::get_Character() method


Grouping Character Default value: U+23DF (BOTTOM CURLY BRACKET)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathGroupingCharacter::get_Character()=0
```

## Remarks


Example: 
```cpp
auto groupingCharacter = System::MakeObject<MathGroupingCharacter>(System::MakeObject<MathematicalText>(u"abc"));
groupingCharacter->set_Character(u'\u23DD');
// Bottom Parenthesis
```

## See Also

* Class [IMathGroupingCharacter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)