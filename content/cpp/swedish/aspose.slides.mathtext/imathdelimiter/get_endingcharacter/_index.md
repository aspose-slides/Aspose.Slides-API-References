---
title: get_EndingCharacter()
second_title: Aspose.Slides för C++ API-referens
description: "Delimiter Ending Character anger den avslutande, eller slutande, avgränsartecknet. Matematiska avgränsare är omslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: ')'."
type: docs
weight: 66
url: /sv/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() metod

Delimiter Ending Character specifies the ending, or closing, delimiter character. Matematiska avgränsare är omslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
```

## Anmärkningar

Exempel:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Se även

* Klass [IMathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)