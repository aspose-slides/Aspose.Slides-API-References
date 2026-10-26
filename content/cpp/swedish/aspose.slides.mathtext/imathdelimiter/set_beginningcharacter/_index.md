---
title: set_BeginningCharacter()
second_title: Aspose.Slides för C++ API-referens
description: "Delimiter Beginning Character specificerar början, eller öppningsavgränsningstecknet. Matematiska avgränsare är omslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: '('."
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) metod

Delimiter Beginning Character specificerar början, eller öppningsavgränsningstecknet. Matematiska avgränsare är omslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## Anmärkningar

Exempel:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Se även

* Klass [IMathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)