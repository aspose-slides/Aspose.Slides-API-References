---
title: get_SeparatorCharacter()
second_title: Aspose.Slides for C++ API Reference
description: "Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'."
type: docs
weight: 40
url: /cpp/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() method


Delimiter Separator Character specifies the character that separates arguments in the delimiter object. The default: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
```

## Remarks


Example: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## See Also

* Class [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
