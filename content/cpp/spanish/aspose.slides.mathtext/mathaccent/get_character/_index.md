---
title: get_Character()
second_title: Referencia de API de Aspose.Slides para C++
description: "Carácter de acento El valor debe estar dentro del rango de (U+0300\\u2013U+036F) o(U+20D0\\u2013U+20EF) Valor predeterminado: Acento circunflejo combinante (U+0302)"
type: docs
weight: 14
url: /es/aspose.slides.mathtext/mathaccent/get_character/
---
## MathAccent::get_Character() método

Carácter de acento El valor debe estar dentro del rango de (U+0300\\u2013U+036F) o(U+20D0\\u2013U+20EF) Valor predeterminado: Combining Circumflex Accent (U+0302)

```cpp
char16_t Aspose::Slides::MathText::MathAccent::get_Character() override
```

## Observaciones

Ejemplo:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Véase también

* Clase [MathAccent](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)