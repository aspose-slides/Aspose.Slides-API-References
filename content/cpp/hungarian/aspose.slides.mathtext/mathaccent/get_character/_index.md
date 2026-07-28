---
title: get_Character()
second_title: Aspose.Slides C++-hez API hivatkozás
description: "Akcent karakter Az értéknek a (U+0300\\u2013U+036F) vagy(U+20D0\\u2013U+20EF) Alapértelmezett érték: Combining Circumflex Accent (U+0302)"
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() metódus

Akcent karakter Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie. Alapértelmezett érték: Combining Circumflex Accent (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## Megjegyzések

Példa: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Lásd még

* Osztály [MathAccent](../)
* Névtere [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)