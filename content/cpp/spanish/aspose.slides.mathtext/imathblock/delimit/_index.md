---
title: Delimit()
second_title: Referencia de la API de Aspose.Slides para C++
description: Delimita todos los elementos hijos con el carácter separador (sin los corchetes)
type: docs
weight: 1
url: /es/aspose.slides.mathtext/imathblock/delimit/
---
## IMathBlock::Delimit(char16_t) método

Delimita todos los elementos hijos con el carácter separador (sin los corchetes)

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Delimit(char16_t separatorCharacter)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separatorCharacter | char16_t | Carácter usado como separador |

### Valor devuelto

Instancia de [IMathDelimiter](../../imathdelimiter/) elemento

## Observaciones

Ejemplo: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathDelimiter](../../imathdelimiter/)
* Clase [IMathBlock](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)