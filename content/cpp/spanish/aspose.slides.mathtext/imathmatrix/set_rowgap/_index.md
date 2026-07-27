---
title: set_RowGap()
second_title: Referencia de API de Aspose.Slides para C++
description: "El valor del espacio vertical entre filas de una matriz; si la RowGapRule está configurada en 3 (\"Exactly\"), la unidad se interpreta como twips (1/20 de punto) si la RowGapRule está configurada en 4 (\"Multiple\"), la unidad se interpreta como medias líneas. Predeterminado: 0"
type: docs
weight: 196
url: /es/aspose.slides.mathtext/imathmatrix/set_rowgap/
---
## IMathMatrix::set_RowGap(uint32_t) método

El valor del espacio vertical entre filas de una matriz; si la RowGapRule está configurada en 3 ("Exactly"), la unidad se interpreta como twips (1/20 de punto). Si la RowGapRule está configurada en 4 ("Multiple"), la unidad se interpreta como medias líneas. Predeterminado: 0

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_RowGap(uint32_t value)=0
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