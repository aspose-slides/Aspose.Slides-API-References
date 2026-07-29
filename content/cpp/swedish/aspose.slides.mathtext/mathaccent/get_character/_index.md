---
title: get_Character()
second_title: Aspose.Slides för C++ API-referens
description: "Accenttecken Värdet bör ligga inom intervallet (U+0300\\u2013U+036F) eller (U+20D0\\u2013U+20EF) Standardvärde: Combining Circumflex Accent (U+0302)"
type: docs
weight: 14
url: /sv/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() metod


Accenttecken Värdet bör ligga inom intervallet (U+0300\\u2013U+036F) eller (U+20D0\\u2013U+20EF) Standardvärde: Combining Circumflex Accent (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
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