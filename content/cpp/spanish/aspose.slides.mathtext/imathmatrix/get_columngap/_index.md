---
title: get_ColumnGap()
second_title: Referencia API de Aspose.Slides para C++
description: "El valor del espacio horizontal entre columnas de una matriz; si ColumnGapRule está configurado en 3 (\"Exactly\"), entonces la unidad se interpreta como twips (1/20 de punto) si ColumnGapRule está configurado en 4 (\"Multiple\"), entonces la unidad se interpreta como número de incrementos de 0,5 em. En otros casos se ignora. Predeterminado: 0"
type: docs
weight: 131
url: /es/aspose.slides.mathtext/imathmatrix/get_columngap/
---
## IMathMatrix::get_ColumnGap() método

El valor del espacio horizontal entre columnas de una matriz; Si ColumnGapRule está configurado en 3 ("Exactly"), entonces la unidad se interpreta como twips (1/20 de punto) Si ColumnGapRule está configurado en 4 ("Multiple"), entonces la unidad se interpreta como número de incrementos de 0.5 em. En otros casos se ignora. Predeterminado: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_ColumnGap()=0
```

## Comentarios

Ejemplo:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::Exactly);
matrix->set_ColumnGap(20);
```

## Ver también

* Clase [IMathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)