---
title: DeleteRow()
second_title: Referencia de API de Aspose.Slides para C++
description: Elimina la fila especificada
type: docs
weight: 300
url: /es/aspose.slides.mathtext/imathmatrix/deleterow/
---
## IMathMatrix::DeleteRow(int32_t) método


Elimina la fila especificada

```cpp
virtual void Asprose::Slides::MathText::IMathMatrix::DeleteRow(int32_t rowIndex)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rowIndex | **int32_t** | El índice basado en cero de la fila a eliminar. |
## Observaciones



Ejemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## Ver también

* Clase [IMathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)