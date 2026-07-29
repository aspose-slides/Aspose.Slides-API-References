---
title: set_EndingCharacter()
second_title: Aspose.Slides för C++ API-referens
description: "Delimiter Ending Character specificerar det avslutande, eller slutande, skiljetecknet. Matematiska skiljetecken är omslutande tecken såsom parenteser, hakparenteser och måsvingar. Standardvärdet: ')'."
type: docs
weight: 79
url: /sv/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---
## MathDelimiter::set_EndingCharacter(char16_t) metod

Delimiter Ending Character specificerar det avslutande, eller slutande, skiljetecknet. Matematiska skiljetecken är omslutande tecken såsom parenteser, hakparenteser och måsvingar. Standardvärdet: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
```

## Anmärkningar

Exempel: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Se även

* Klass [MathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)