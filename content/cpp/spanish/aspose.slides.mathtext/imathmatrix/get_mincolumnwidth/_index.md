---
title: get_MinColumnWidth()
second_title: Referencia de API de Aspose.Slides para C++
description: "Ancho mínimo de columna en twips (1/20 de punto) El espacio de separación (también llamado \\u201CColumn Gap\\u201D o \\u201CGap Width\\u201D) se agrega al MinColumnWidth para determinar el espaciamiento total de la matriz de columnas (distancia entre los mismos bordes de diferentes columnas). Predeterminado: 0."
type: docs
weight: 79
url: /es/aspose.slides.mathtext/imathmatrix/get_mincolumnwidth/
---
## IMathMatrix::get_MinColumnWidth() método


Ancho mínimo de columna en twips (1/20 de punto) El espacio de separación (también llamado “Column Gap” o “Gap Width”) se agrega al MinColumnWidth para determinar el total Matrix [Column](../../../aspose.slides/column/) Spacing (distancia entre los mismos bordes de diferentes columnas). Predeterminado: 0.

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_MinColumnWidth()=0
```

## Observaciones


Ejemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## Véase también

* Clase [IMathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)