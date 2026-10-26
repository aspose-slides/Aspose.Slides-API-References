---
title: Enclose()
second_title: Referencia de la API de Aspose.Slides para C++
description: Encierra un elemento matemático entre paréntesis
type: docs
weight: 40
url: /es/aspose.slides.mathtext/imathelement/enclose/
---
## IMathElement::Enclose() método


Encierra un elemento matemático entre paréntesis

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose()=0
```


### Valor de retorno

El elemento matemático de tipo [IMathDelimiter](../../imathdelimiter/) que incluye los paréntesis
## Observaciones



Ejemplo: 
```cpp
auto element = System::MakeObject<MathematicalText>(u"x");
auto delimiter = element->Enclose();
```

## IMathElement::Enclose(char16_t, char16_t) método


Encierra este elemento en los caracteres especificados, como paréntesis u otros caracteres como marco

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathElement::Enclose(char16_t beginningCharacter, char16_t endingCharacter)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| beginningCharacter | char16_t | Carácter inicial (normalmente corchete izquierdo) |
| endingCharacter | char16_t | Carácter final (normalmente corchete derecho) |

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
* Clase [IMathElement](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)