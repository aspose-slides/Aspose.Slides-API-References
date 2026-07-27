---
title: Delimit()
second_title: Referencia de API de Aspose.Slides para C++
description: Delimita los elementos secundarios con el carácter separador (sin los corchetes)
type: docs
weight: 209
url: /es/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) método

Delimita los elementos secundarios con el carácter separador (sin los corchetes)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| separatorCharacter | char16_t | Carácter separador |

### Valor devuelto

El elemento matemático de tipo [IMathDelimiter](../../imathdelimiter/)
## Observaciones



Ejemplo: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathDelimiter](../../imathdelimiter/)
* Clase [MathBlock](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)