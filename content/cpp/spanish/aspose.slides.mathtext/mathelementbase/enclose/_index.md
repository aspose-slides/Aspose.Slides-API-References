---
title: Enclose()
second_title: Referencia de API de Aspose.Slides para C++
description: Encierra un elemento matemático entre paréntesis
type: docs
weight: 27
url: /es/aspose.slides.mathtext/mathelementbase/enclose/
---
## MathElementBase::Enclose() método

Encierra un elemento matemático entre paréntesis

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose() override
```

### Valor de retorno

El elemento matemático de tipo [IMathDelimiter](../../imathdelimiter/) que incluye los paréntesis
## Observaciones



Ejemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## MathElementBase::Enclose(char16_t, char16_t) método

Encierra un elemento matemático en los caracteres especificados, como paréntesis u otros caracteres como marco

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathElementBase::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| beginningCharacter | char16_t | Carácter inicial (usualmente corchete izquierdo) |
| endingCharacter | char16_t | Carácter final (usualmente corchete derecho) |

### Valor de retorno

El elemento matemático de tipo [IMathDelimiter](../../imathdelimiter/) que incluye los caracteres especificados como marco
## Observaciones



Ejemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose(u'[', u']');
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathDelimiter](../../imathdelimiter/)
* Clase [MathElementBase](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)