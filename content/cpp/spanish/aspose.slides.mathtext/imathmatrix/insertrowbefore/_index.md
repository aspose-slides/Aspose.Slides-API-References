---
title: InsertRowBefore()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserta una nueva fila antes de la especificada. Inicialmente, todos los elementos en la nueva fila son nulos.
type: docs
weight: 274
url: /es/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) método

Inserta una nueva fila antes de la especificada. Inicialmente, todos los elementos en la nueva fila son nulos.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
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

* Clase [IMathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)