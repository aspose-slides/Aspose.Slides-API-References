---
title: idx_get()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elemento de la matriz
type: docs
weight: 209
url: /es/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) método

Elemento de la matriz

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| row | **int32_t** | El índice basado en cero de la fila para obtener el elemento |
| column | **int32_t** | El índice basado en cero de la columna para obtener el elemento |

### Valor de retorno


## Observaciones



Ejemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IMathElement](../../imathelement/)
* Clase [MathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)