---
title: InsertRowAfter()
second_title: Referencia de la API de Aspose.Slides para C++
description: Inserte una nueva fila después de la especificada. Inicialmente, todos los elementos en la nueva fila son nulos.
type: docs
weight: 300
url: /es/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) método

Inserte una nueva fila después de la especificada. Inicialmente, todos los elementos en la nueva fila son nulos.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rowIndex | **int32_t** | Índice de la fila después de la cual insertar una nueva |
## Observaciones



Ejemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## Ver también

* Clase [MathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)