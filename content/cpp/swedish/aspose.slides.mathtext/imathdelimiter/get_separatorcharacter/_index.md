---
title: get_SeparatorCharacter()
second_title: "Aspose.Slides för C++ API-referens"
description: "Delimiter Separator Character specificerar tecknet som separerar argumenten i delimiter-objektet. Standardvärdet: '|'."
type: docs
weight: 40
url: /sv/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() metod

Delimiter Separator Character specificerar tecknet som separerar argumenten i delimiter-objektet. Standardvärdet: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
```

## Anmärkningar

Exempel:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## Se även

* Klass [IMathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)