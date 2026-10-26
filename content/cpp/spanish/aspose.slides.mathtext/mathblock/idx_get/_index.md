---
title: idx_get()
second_title: Referencia de API de Aspose.Slides para C++
description: Obtiene IMathElement en el índice especificado.
type: docs
weight: 27
url: /es/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) método

Obtiene [IMathElement](../../imathelement/) en el índice especificado.

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | **int32_t** | El índice basado en cero del elemento |

### Valor de retorno

El elemento matemático.

## Observaciones



Ejemplo: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathBlock](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)