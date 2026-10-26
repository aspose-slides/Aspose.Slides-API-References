---
title: get_Character()
second_title: Aspose.Slides pro C++ API Reference
description: "Znak akcentu Hodnota by měla být v rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF) Výchozí hodnota: Combining Circumflex Accent (U+0302)"
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/imathaccent/get_character/
---
## IMathAccent::get_Character() metoda

Znak akcentu Hodnota by měla být v rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF) Výchozí hodnota: Combining Circumflex Accent (U+0302)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathAccent::get_Character()=0
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