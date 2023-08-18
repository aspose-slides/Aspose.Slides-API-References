---
title: get_SeparatorCharacter()
second_title: Aspose.Slides for C++ API Reference
description: "Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'."
type: docs
weight: 40
url: /aspose.slides.mathtext/mathdelimiter/get_separatorcharacter/
---
## MathDelimiter::get_SeparatorCharacter() method


Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_SeparatorCharacter() override
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