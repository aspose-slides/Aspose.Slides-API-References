---
title: set_Character()
second_title: Aspose.Slides C++ API referencia
description: "Az értéknek a tartományon belül kell lennie (U+0300\\u2013U+036F) vagy(U+20D0\\u2013U+20EF) Alapértelmezett érték: Kombináló körülíró akcent (U+0302)"
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) metódus


Akcent karakter Az értéknek a tartományon belül kell lennie (U+0300\\u2013U+036F) vagy(U+20D0\\u2013U+20EF) Alapértelmezett érték: Kombináló körülíró akcent (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## Megjegyzések


Példa: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Lásd még

* Osztály [IMathAccent](../)
* Névterület [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)