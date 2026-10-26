---
title: GetColumnAlignment()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene la alineación horizontal de la columna especificada
type: docs
weight: 235
url: /es/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) método


Obtiene la alineación horizontal de la columna especificada

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | **int32_t** | Índice de columna basado en cero |

### Valor de retorno

Alineación horizontal de la columna especificada
## Observaciones



Ejemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## Ver también

* Enumeración [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Clase [IMathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)