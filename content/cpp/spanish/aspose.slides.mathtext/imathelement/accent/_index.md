---
title: Accent()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece una marca de acento (un carácter en la parte superior de este elemento)
type: docs
weight: 209
url: /es/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) método

Establece una marca de acento (un carácter en la parte superior de este elemento)

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| accentCharacter | char16_t | Carácter de acento. El valor debe estar dentro del rango de (U+0300\\u2013U+036F) o (U+20D0\\u2013U+20EF) |

### Valor devuelto

Nueva instancia del tipo [IMathAccent](../../imathaccent/)
## Observaciones



Ejemplo: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathAccent](../../imathaccent/)
* Class [IMathElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)