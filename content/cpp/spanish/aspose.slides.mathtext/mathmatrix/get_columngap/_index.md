---
title: get_ColumnGap()
second_title: Referencia de API de Aspose.Slides para C++
description: "El valor del espacio horizontal entre columnas de una matriz; Si la ColumnGapRule se establece en 3 (\"Exactly\"), entonces la unidad se interpreta como twips (1/20 de un punto) Si la ColumnGapRule se establece en 4 (\"Multiple\"), entonces la unidad se interpreta como número de incrementos de 0.5 em. En otros casos se ignora. Predeterminado: 0"
type: docs
weight: 131
url: /es/aspose.slides.mathtext/mathmatrix/get_columngap/
---
## MathMatrix::get_ColumnGap() método


El valor del espacio horizontal entre columnas de una matriz; Si la ColumnGapRule se establece en 3 ("Exactly"), entonces la unidad se interpreta como twips (1/20 de un punto) Si la ColumnGapRule se establece en 4 ("Multiple"), entonces la unidad se interpreta como número de incrementos de 0.5 em. En otros casos se ignora. Predeterminado: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_ColumnGap() override
```

## Observaciones


Ejemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Ver también

* Clase [MathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)