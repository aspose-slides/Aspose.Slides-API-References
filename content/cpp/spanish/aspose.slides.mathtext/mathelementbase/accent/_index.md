---
title: Accent()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece una marca de acento (un carácter en la parte superior de este elemento)
type: docs
weight: 196
url: /es/aspose.slides.mathtext/mathelementbase/accent/
---
## MathElementBase::Accent(char16_t) método

Establece una marca de acento (un carácter en la parte superior de este elemento)

```cpp
System::SharedPtr<IMathAccent> Aspose::Slides::MathText::MathElementBase::Accent(char16_t accentCharacter) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| accentCharacter | char16_t | Carácter de acento. El valor debe estar dentro del rango de (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) |

### Valor devuelto

Nueva instancia del tipo [IMathAccent](../../imathaccent/)
## Observaciones

Ejemplo:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathAccent](../../imathaccent/)
* Clase [MathElementBase](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)