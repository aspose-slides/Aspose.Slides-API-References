---
title: set_SeparatorCharacter()
second_title: Aspose.Slides för C++ API-referens
description: "Delimiter Separator Character specificerar tecknet som separerar argument i delimiter-objektet. Standardvärdet: '|'."
type: docs
weight: 53
url: /sv/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) metod

Delimiter Separator Character specificerar tecknet som separerar argument i delimiter-objektet. Standardvärdet: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## Anmärkningar

Exempel: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Se också

* Klass [IMathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)