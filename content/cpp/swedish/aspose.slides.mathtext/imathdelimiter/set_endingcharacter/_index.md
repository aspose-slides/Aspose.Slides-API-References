---
title: set_EndingCharacter()
second_title: Aspose.Slides för C++ API-referens
description: "Avgränsarnas sluttecken anger det avslutande, eller stängande, avgränsartecknet. Matematiska avgränsare är omslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: ')'."
type: docs
weight: 79
url: /sv/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMMathDelimiter::set_EndingCharacter(char16_t) metod

Delimiter Ending Character anger den avslutande, eller slutande, avgränsartecknet. Matematiska avgränsare är omslutande tecken som parenteser, hakparenteser och klammerparenteser. Standardvärdet: ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
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