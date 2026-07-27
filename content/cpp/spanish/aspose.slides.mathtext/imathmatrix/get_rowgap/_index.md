---
title: get_RowGap()
second_title: Referencia de API de Aspose.Slides para C++
description: "El valor del espacio vertical entre filas de una matriz; Si el RowGapRule está configurado a 3 (\"Exactly\"), entonces la unidad se interpreta como twips (1/20 de un punto) Si el RowGapRule está configurado a 4 (\"Multiple\"), entonces la unidad se interpreta como medias líneas. Predeterminado: 0"
type: docs
weight: 183
url: /es/aspose.slides.mathtext/imathmatrix/get_rowgap/
---
## IMathMatrix::get_RowGap() método

El valor del espacio vertical entre filas de una matriz; Si el RowGapRule está configurado a 3 ("Exactly"), entonces la unidad se interpreta como twips (1/20 de un punto) Si el RowGapRule está configurado a 4 ("Multiple"), entonces la unidad se interpreta como medias líneas. Predeterminado: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_RowGap()=0
```

## Observaciones

Ejemplo:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_RowGapRule(MathSpacingRules::Exactly);
matrix->set_RowGap(20);
```

## Ver también

* Clase [IMathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)