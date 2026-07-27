---
title: InsertColumnBefore()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserte una nueva columna antes de la especificada. Inicialmente, todos los elementos de la nueva columna son nulos.
type: docs
weight: 313
url: /es/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) método


Inserte una nueva columna antes de la especificada. Inicialmente, todos los elementos de la nueva columna son nulos.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
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

* Clase [IMathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)