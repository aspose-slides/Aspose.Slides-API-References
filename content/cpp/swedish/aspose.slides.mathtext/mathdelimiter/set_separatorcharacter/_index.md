---
title: set_SeparatorCharacter()
second_title: Aspose.Slides för C++ API-referens
description: "Delimiter Separator Character specificerar tecknet som separerar argumenten i delimiter-objektet. Standardvärdet: '|'."
type: docs
weight: 53
url: /sv/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) metod

Delimiter Separator Character specificerar tecknet som separerar argumenten i delimiter-objektet. Standardvärdet: '|'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## Anmärkningar

Exempel:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Se även

* Klass [MathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)