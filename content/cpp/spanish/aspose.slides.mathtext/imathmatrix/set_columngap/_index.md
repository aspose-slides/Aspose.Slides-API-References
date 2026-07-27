---
title: set_ColumnGap()
second_title: Referencia de API de Aspose.Slides para C++
description: "El valor del espacio horizontal entre columnas de una matriz; si la ColumnGapRule se establece en 3 (\"Exactly\"), entonces la unidad se interpreta como twips (1/20 de punto) si la ColumnGapRule se establece en 4 (\"Multiple\"), entonces la unidad se interpreta como número de incrementos de 0.5 em. En otros casos se ignora. Predeterminado: 0"
type: docs
weight: 144
url: /es/aspose.slides.mathtext/imathmatrix/set_columngap/
---
## IMathMatrix::set_ColumnGap(uint32_t) método

El valor del espacio horizontal entre columnas de una matriz; si la ColumnGapRule se establece en 3 ("Exactly"), entonces la unidad se interpreta como twips (1/20 de punto) si la ColumnGapRule se establece en 4 ("Multiple"), entonces la unidad se interpreta como número de incrementos de 0.5 em. En otros casos se ignora. Predeterminado: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_ColumnGap(uint32_t value)=0
```

## Observaciones

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