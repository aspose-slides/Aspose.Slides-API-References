---
title: get_MinColumnWidth()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Ancho mínimo de columna en twips (1/20 de un punto) El espaciado de la brecha (también referido como \\u201CColumn Gap\\u201D o \\u201CGap Width\\u201D) se añade al MinColumnWidth para determinar el total Matrix Column Spacing (distancia entre los mismos bordes de diferentes columnas). Predeterminado: 0."
type: docs
weight: 79
url: /es/aspose.slides.mathtext/mathmatrix/get_mincolumnwidth/
---
## MathMatrix::get_MinColumnWidth() método

Ancho mínimo de columna en twips (1/20 de un punto) El espaciado de la brecha (también referido como \\u201CColumn Gap\\u201D o \\u201CGap Width\\u201D) se añade al MinColumnWidth para determinar el total Matrix [Column](../../../aspose.slides/column/) Spacing (distancia entre los mismos bordes de diferentes columnas). Predeterminado: 0.

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_MinColumnWidth() override
```

## Observaciones

Ejemplo:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## Ver también

* Clase [MathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)