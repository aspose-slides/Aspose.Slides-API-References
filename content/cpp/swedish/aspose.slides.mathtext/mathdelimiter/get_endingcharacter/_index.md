---
title: get_EndingCharacter()
second_title: Aspose.Slides för C++ API-referens
description: "Delimiter Ending Character specificerar det avslutande, eller slutande, avgränsningstecknet. Matematiska avgränsare är omslutande tecken såsom parenteser, hakparenteser och måsvingar. Standardvärdet: ')'."
type: docs
weight: 66
url: /sv/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() metod


Delimiter Ending Character specificerar det avslutande, eller slutande, avgränsningstecknet. Matematiska avgränsare är omslutande tecken såsom parenteser, hakparenteser och måsvingar. Standardvärdet: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## Anmärkningar


Exempel: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Se också

* Klass [MathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)