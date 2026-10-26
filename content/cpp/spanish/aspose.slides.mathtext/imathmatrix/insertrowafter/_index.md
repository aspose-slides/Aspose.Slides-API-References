---
title: InsertRowAfter()
second_title: Referencia de API de Aspose.Slides para C++
description: Inserta una nueva fila después de la especificada. Inicialmente, todos los elementos en la nueva fila son nulos.
type: docs
weight: 287
url: /es/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) método

Inserta una nueva fila después de la especificada. Inicialmente, todos los elementos en la nueva fila son nulos.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
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

## Véase también

* Clase [IMathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)