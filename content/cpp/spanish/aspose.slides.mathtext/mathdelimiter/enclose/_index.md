---
title: Enclose()
second_title: Referencia de API de Aspose.Slides para C++
description: Encierra un elemento matemático en caracteres especificados, como paréntesis u otros caracteres como marco
type: docs
weight: 170
url: /es/aspose.slides.mathtext/mathdelimiter/enclose/
---
## MathDelimiter::Enclose(char16_t, char16_t) method

Encierra un elemento matemático en caracteres especificados, como paréntesis u otros caracteres como marco

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathDelimiter::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| beginningCharacter | char16_t | Carácter inicial (normalmente corchete izquierdo) |
| endingCharacter | char16_t | Carácter final (normalmente corchete derecho) |

### Valor devuelto

Si *beginningCharacter* y *endingCharacter* son nulos, las propiedades correspondientes solo se les asignan valores y no se crea un nuevo objeto (devuelve esta instancia). De lo contrario, devuelve un nuevo elemento matemático de tipo Delimiter que incluye los caracteres especificados como marco y esta instancia de [MathDelimiter](../) enmarcada dentro.

## Comentarios

## Ejemplo:
```cpp
auto innerDelimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u",y"))->Enclose(u'{', u'}');
auto outerDelimiter = innerDelimiter->Enclose(u'[', u']');
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathDelimiter](../../imathdelimiter/)
* Clase [MathDelimiter](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)