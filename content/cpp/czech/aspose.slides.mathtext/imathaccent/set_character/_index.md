---
title: set_Character()
second_title: Aspose.Slides pro C++ – reference API
description: "Znak akcentu Hodnota by měla být v rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF) Výchozí hodnota: Combining Circumflex Accent (U+0302)"
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) metoda

Znak akcentu Hodnota by měla být v rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF) Výchozí hodnota: Combining Circumflex Accent (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## Poznámky

Příklad:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Viz také

* Třída [IMathAccent](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)