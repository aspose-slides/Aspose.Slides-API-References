---
title: idx_get()
second_title: Referencia de API de Aspose.Slides para C++
description: Elementos de la matriz
type: docs
weight: 209
url: /es/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) method


Elementos de la matriz

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
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
* Clase [IMathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)