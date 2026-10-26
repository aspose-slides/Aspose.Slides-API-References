---
title: InsertColumnBefore()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserta una nueva columna antes de la especificada. Inicialmente, todos los elementos en la nueva columna son nulos.
type: docs
weight: 326
url: /es/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) método

Inserta una nueva columna antes de la especificada. Inicialmente, todos los elementos en la nueva columna son nulos.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| columnIndex | **int32_t** | Índice de la columna antes de la cual insertar una nueva |
## Observaciones

Ejemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## Ver también

* Clase [MathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)