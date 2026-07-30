---
title: set_Character()
second_title: Aspose.Slides pro C++ referenci API
description: "Znak akcentu Hodnota by měla být v rozmezí (U+0300\\u2013U+036F) nebo(U+20D0\\u2013U+20EF) Výchozí hodnota: Kombinující střechový akcent (U+0302)"
type: docs
weight: 27
url: /cs/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) metoda


Znak akcentu Hodnota by měla být v rozmezí (U+0300\\u2013U+036F) nebo (U+20D0\\u2013U+20EF) Výchozí hodnota: Kombinující stříškový akcent (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
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