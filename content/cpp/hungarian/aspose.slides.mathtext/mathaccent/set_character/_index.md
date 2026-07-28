---
title: set_Character()
second_title: Aspose.Slides C++ API referencia
description: "Accent karakter Az értéknek a (U+0300\\u2013U+036F) vagy (U+20D0\\u2013U+20EF) tartományon belül kell lennie Alapértelmezett érték: Combining Circumflex Accent (U+0302)"
type: docs
weight: 27
url: /hu/aspose.slides.mathtext/mathaccent/set_character/
---
## MathAccent::set_Character(char16_t) metódus

Accent karakter Az értéknek a (U+0300\u2013U+036F) vagy (U+20D0\u2013U+20EF) tartományon belül kell lennie Alapértelmezett érték: Combining Circumflex Accent (U+0302)

```cpp
void Aspose::Slides::MathText::MathAccent::set_Character(char16_t value) override
```

## Megjegyzések

Példa: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Lásd még

* Osztály [MathAccent](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)