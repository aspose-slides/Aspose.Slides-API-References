---
title: get_Character()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: "Znak akcentu Hodnota by měla být v rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF). Výchozí hodnota: Kombinovaný stříškový akcent (U+0302)"
type: docs
weight: 14
url: /cs/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() metoda

Znak akcentu Hodnota by měla být v rozsahu (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF). Výchozí hodnota: Kombinovaný stříškový akcent (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## Poznámky

Příklad: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Viz také

* Třída [MathAccent](../)
* Jmenný prostor [Aspose::Slides::MathText](../../)
* Knihovna [Aspose.Slides](../../../)