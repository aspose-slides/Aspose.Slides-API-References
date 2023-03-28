---
title: set_SeparatorCharacter()
second_title: Aspose.Slides for C++ API Reference
description: "Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'."
type: docs
weight: 53
url: /cpp/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) method


Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## Remarks


Example: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## See Also

* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
