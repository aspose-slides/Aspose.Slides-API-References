---
title: InsertColumnAfter()
second_title: Referencia de la API de Aspose.Slides para C++
description: Inserta una nueva columna después de la especificada Inicialmente todos los elementos en la nueva columna son nulos.
type: docs
weight: 339
url: /es/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) method


Inserta una nueva columna después de la especificada. Inicialmente todos los elementos en la nueva columna son nulos.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
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

* Clase [MathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)