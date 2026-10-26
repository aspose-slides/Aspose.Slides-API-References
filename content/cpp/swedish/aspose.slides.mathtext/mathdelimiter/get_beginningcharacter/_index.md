---
title: get_BeginningCharacter()
second_title: Aspose.Slides för C++ API-referens
description: "Delimiter Beginning Character specificerar början, eller öppning, avgränsartecknet. Matematiska avgränsare är omslutande tecken såsom parenteser, hakparenteser och måsvingar. Standardvärdet: '('."
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() metod


Delimiter Beginning Character specificerar början, eller öppning, av avgränsartecknet. Matematiska avgränsare är omslutande tecken såsom parenteser, hakparenteser och måsvingar. Standardvärdet: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## Anmärkningar


Exempel: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Se också

* Klass [MathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)