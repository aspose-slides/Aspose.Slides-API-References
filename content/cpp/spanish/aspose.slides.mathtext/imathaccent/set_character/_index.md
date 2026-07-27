---
title: set_Character()
second_title: Referencia de API de Aspose.Slides para C++
description: "Carácter de acento El valor debe estar dentro del rango de (U+0300\\u2013U+036F) o(U+20D0\\u2013U+20EF) Valor predeterminado: Acento circunflejo combinante (U+0302)"
type: docs
weight: 27
url: /es/aspose.slides.mathtext/imathaccent/set_character/
---
## IMathAccent::set_Character(char16_t) método


Carácter de acento El valor debe estar dentro del rango de (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) Valor predeterminado: Acento circunflejo combinante (U+0302)

```cpp
virtual void Aspose::Slides::MathText::IMathAccent::set_Character(char16_t value)=0
```

## Observaciones


Ejemplo: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
char16_t ch = accent->get_Character();
```

## Ver también

* Clase [IMathAccent](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)