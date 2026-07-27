---
title: InsertColumnAfter()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserta una nueva columna después de la especificada. Inicialmente, todos los elementos de la nueva columna son nulos.
type: docs
weight: 326
url: /es/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) método


Inserta una nueva columna después de la especificada. Inicialmente, todos los elementos de la nueva columna son nulos.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | **int32_t** | Índice de la columna después de la cual insertar una nueva |

## Observaciones


Ejemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## Ver también

* Clase [IMathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)