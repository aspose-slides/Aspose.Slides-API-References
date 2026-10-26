---
title: Enclose()
second_title: Referencia de API de Aspose.Slides para C++
description: Encierra los elementos secundarios de este bloque en los caracteres especificados, como paréntesis u otros, como marco y los delimita con un carácter separador
type: docs
weight: 14
url: /es/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) método


Encierra los elementos secundarios de este bloque en los caracteres especificados, como paréntesis u otros, como marcaje y los delimita con un carácter separador

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| beginningCharacter | char16_t | Carácter inicial (usualmente corchete izquierdo) |
| endingCharacter | char16_t | Carácter final (usualmente corchete derecho) |
| separatorCharacter | char16_t | Carácter separador |

### Valor de retorno

El elemento matemático de tipo [IMathDelimiter](../../imathdelimiter/) que incluye los caracteres especificados como marco y delimitador

## Observaciones



Ejemplo: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathDelimiter](../../imathdelimiter/)
* Clase [IMathBlock](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)