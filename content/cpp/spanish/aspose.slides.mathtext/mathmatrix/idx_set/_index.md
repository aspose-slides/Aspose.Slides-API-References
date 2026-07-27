---
title: idx_set()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elemento de la matriz
type: docs
weight: 222
url: /es/aspose.slides.mathtext/mathmatrix/idx_set/
---
## MathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) método

Elemento de la matriz

```cpp
void Aspose::Slides::MathText::MathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| row | **int32_t** | El índice basado en cero de la fila row para obtener el elemento |
| column | **int32_t** | El índice basado en cero de la columna column para obtener el elemento |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |
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