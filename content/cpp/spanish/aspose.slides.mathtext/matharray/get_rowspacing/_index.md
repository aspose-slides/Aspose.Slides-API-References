---
title: get_RowSpacing()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Espaciado entre filas de una matriz Se usa solo cuando RowSpacingRule está establecido en 3 Exactamente, en cuyo caso la unidad de medida es puntos o Multiple, en cuyo caso la unidad de medida es medias líneas. Predeterminado: 0"
type: docs
weight: 118
url: /es/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() método


Espaciado entre filas de una matriz. Se usa solo cuando RowSpacingRule está establecido en 3 Exactamente, en cuyo caso la unidad de medida son puntos o Multiple, en cuyo caso la unidad de medida son medias líneas. Predeterminado: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## Observaciones


Ejemplo:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Véase también

* Clase [MathArray](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)