---
title: get_RowGap()
second_title: Referencia de API de Aspose.Slides para C++
description: "El valor del espaciado vertical entre filas de una matriz; si RowGapRule está configurado en 3 (\"Exactly\"), entonces la unidad se interpreta como twips (1/20 de un punto) si RowGapRule está configurado en 4 (\"Multiple\"), entonces la unidad se interpreta como medias líneas. Predeterminado: 0"
type: docs
weight: 183
url: /es/aspose.slides.mathtext/mathmatrix/get_rowgap/
---
## MathMatrix::get_RowGap() método


El valor del espaciado vertical entre filas de una matriz; si RowGapRule está configurado en 3 (\"Exactly\"), entonces la unidad se interpreta como twips (1/20 de un punto) si RowGapRule está configurado en 4 (\"Multiple\"), entonces la unidad se interpreta como medias líneas. Predeterminado: 0

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_RowGap() override
```

## Comentarios


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