---
title: set_ColumnGap()
second_title: Referencia de API de Aspose.Slides para C++
description: "El valor del espaciado horizontal entre columnas de una matriz; Si ColumnGapRule está configurado a 3 (\"Exactly\"), entonces la unidad se interpreta como twips (1/20 de un punto) Si ColumnGapRule está configurado a 4 (\"Multiple\"), entonces la unidad se interpreta como número de incrementos de 0.5 em. En otros casos se ignora. Predeterminado: 0"
type: docs
weight: 144
url: /es/aspose.slides.mathtext/mathmatrix/set_columngap/
---
## MathMatrix::set_ColumnGap(uint32_t) método

El valor del espaciado horizontal entre columnas de una matriz; Si ColumnGapRule está configurado a 3 ("Exactly"), entonces la unidad se interpreta como twips (1/20 de un punto) Si ColumnGapRule está configurado a 4 ("Multiple"), entonces la unidad se interpreta como número de incrementos de 0.5 em. En otros casos se ignora. Predeterminado: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_ColumnGap(uint32_t value) override
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