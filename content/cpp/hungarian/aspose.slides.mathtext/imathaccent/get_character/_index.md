---
title: get_Character()
second_title: Aspose.Slides for C++ API referencia
description: "Akcentus karakter Az értéknek a (U+0300\\u2013U+036F) vagy(U+20D0\\u2013U+20EF) tartományon belül kell lennie Alapértelmezett érték: Kombináló körülíró akcentus (U+0302)"
type: docs
weight: 14
url: /hu/aspose.slides.mathtext/imathaccent/get_character/
---
## IMathAccent::get_Character() metódus


Akcentus karakter Az értéknek a következő tartományon belül kell lennie (U+0300\\u2013U+036F) vagy(U+20D0\\u2013U+20EF) Alapértelmezett érték: Kombináló körülíró akcentus (U+0302)

```cpp
virtual char16_t Aspose::Slides::MathText::IMathAccent::get_Character()=0
```

## Megjegyzések


Példa: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Lásd még

* Osztály [IMathAccent](../)
* Névtér [Aspose::Slides::MathText](../../)
* Könyvtár [Aspose.Slides](../../../)