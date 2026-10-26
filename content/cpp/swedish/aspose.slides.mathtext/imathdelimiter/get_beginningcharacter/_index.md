---
title: get_BeginningCharacter()
second_title: Aspose.Slides för C++ API-referens
description: "Delimiter Beginning Character specificerar det inledande, eller öppnings, avgränsartecknet. Matematiska avgränsare är omslutande tecken som parenteser, hakparenteser och klammerparenteser. Standardvärdet: '('."
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() metod


Delimiter Beginning Character specificerar den inledande, eller öppnings, avgränsartecknet. Matematiska avgränsare är omslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
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