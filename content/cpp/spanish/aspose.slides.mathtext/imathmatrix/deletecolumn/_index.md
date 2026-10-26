---
title: DeleteColumn()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina la columna especificada
type: docs
weight: 339
url: /es/aspose.slides.mathtext/imathmatrix/deletecolumn/
---
## IMathMatrix::DeleteColumn(int32_t) método

Elimina la columna especificada

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteColumn(int32_t columnIndex)=0
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | **int32_t** | El índice basado en cero de la columna a eliminar. |
## Observaciones


Ejemplo:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## Ver también

* Clase [IMathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)