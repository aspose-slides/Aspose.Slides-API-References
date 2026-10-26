---
title: Enclose()
second_title: Referencia de API de Aspose.Slides para C++
description: Encierra los elementos hijos de este bloque en los caracteres especificados, como paréntesis u otros caracteres como marco
type: docs
weight: 222
url: /es/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) método

Encierra los elementos hijos de este bloque en los caracteres especificados, como paréntesis u otros caracteres como marco

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| beginningCharacter | char16_t | Carácter inicial (usualmente corchete izquierdo) |
| endingCharacter | char16_t | Carácter final (usualmente corchete derecho) |

### Valor devuelto

El elemento matemático de tipo [IMathDelimiter](../../imathdelimiter/) que incluye los caracteres especificados como marco
## Comentarios

Ejemplo: 
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) método


Encierra los elementos hijos de este bloque en los caracteres especificados, como paréntesis u otros, como marco y los delimita con un carácter separador

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| beginningCharacter | char16_t | Carácter inicial (usualmente corchete izquierdo) |
| endingCharacter | char16_t | Carácter final (usualmente corchete derecho) |
| separatorCharacter | char16_t | Carácter separador |

### Valor devuelto

El elemento matemático de tipo [IMathDelimiter](../../imathdelimiter/) que incluye los caracteres especificados como marco y delimitador
## Comentarios

Ejemplo: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathDelimiter](../../imathdelimiter/)
* Clase [MathBlock](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)