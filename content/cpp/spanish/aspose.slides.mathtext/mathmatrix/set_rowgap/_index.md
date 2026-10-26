---
title: set_RowGap()
second_title: Referencia de la API de Aspose.Slides para C++
description: "El valor del espaciado vertical entre filas de una matriz; Si el RowGapRule está configurado en 3 (\"Exactly\"), entonces la unidad se interpreta como twips (1/20 de punto) Si el RowGapRule está configurado en 4 (\"Multiple\"), entonces la unidad se interpreta como medias líneas. Predeterminado: 0"
type: docs
weight: 196
url: /es/aspose.slides.mathtext/mathmatrix/set_rowgap/
---
## MathMatrix::set_RowGap(uint32_t) método

El valor del espaciado vertical entre filas de una matriz; Si el RowGapRule está configurado en 3 ("Exactly"), entonces la unidad se interpreta como twips (1/20 de punto) Si el RowGapRule está configurado en 4 ("Multiple"), entonces la unidad se interpreta como medias líneas. Predeterminado: 0

```cpp
void Aspose::Slides::MathText::MathMatrix::set_RowGap(uint32_t value) override
```

## Observaciones

Ejemplo:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Ver también

* Clase [MathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)