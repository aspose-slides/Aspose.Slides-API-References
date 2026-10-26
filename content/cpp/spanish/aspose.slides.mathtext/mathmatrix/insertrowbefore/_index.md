---
title: InsertRowBefore()
second_title: Referencia de la API de Aspose.Slides para C++
description: Inserta una nueva fila antes de la especificada. Inicialmente, todos los elementos de la nueva fila son nulos.
type: docs
weight: 287
url: /es/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) método


Inserte una nueva fila antes de la especificada. Inicialmente, todos los elementos en la nueva fila son nulos.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rowIndex | **int32_t** | Índice de la fila antes de la cual insertar una nueva |
## Observaciones



Ejemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## Ver también

* Clase [MathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)