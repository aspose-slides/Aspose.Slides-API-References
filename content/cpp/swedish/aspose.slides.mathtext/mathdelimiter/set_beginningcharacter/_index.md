---
title: set_BeginningCharacter()
second_title: Aspose.Slides för C++ API-referens
description: "Delimiter Beginning Character specificerar början, eller öppningstecknet, för avgränsartecknet. Matematiska avgränsare är omslutande tecken såsom parenteser, hakparenteser och klammerparenteser. Standardvärdet: '('."
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/mathdelimiter/set_beginningcharacter/
---
## MathDelimiter::set_BeginningCharacter(char16_t) metod

Delimiter Beginning Character specifies the beginning, or opening, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: '('.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_BeginningCharacter(char16_t value) override
```

## Anmärkningar

Exempel: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Se även

* Klass [MathDelimiter](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)