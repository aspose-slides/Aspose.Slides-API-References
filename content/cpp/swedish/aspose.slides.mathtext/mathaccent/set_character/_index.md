---
title: set_Character()
second_title: Aspose.Slides för C++ API-referens
description: "Accenttecken Värdet bör ligga inom intervallet (U+0300\\u2013U+036F) eller(U+20D0\\u2013U+20EF) Standardvärde: Kombinerande cirkumflexaccent (U+0302)"
type: docs
weight: 27
url: /sv/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) metod

Accenttecken Värdet bör ligga inom intervallet (U+0300\\u2013U+036F) eller(U+20D0\\u2013U+20EF) Standardvärde: Kombinerande cirkumflexaccent (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
```

## Anmärkningar


Exempel:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Se även

* Klass [MathAccent](../)
* Namnrymd [Aspose::Slides::MathText](../../)
* Bibliotek [Aspose.Slides](../../../)