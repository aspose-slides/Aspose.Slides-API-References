---
title: set_RowSpacing()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Espaciado entre filas de una matriz Se usa solo cuando RowSpacingRule está configurado a 3 Exactamente en cuyo caso la unidad de medida son puntos o Multiple en cuyo caso la unidad de medida son medias líneas. Predeterminado: 0"
type: docs
weight: 131
url: /es/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) método

Espaciado entre filas de una matriz Se usa solo cuando RowSpacingRule está configurado a 3 Exactamente en cuyo caso la unidad de medida son puntos o Multiple en cuyo caso la unidad de medida son medias líneas. Predeterminado: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
```

## Observaciones

Ejemplo: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Ver también

* Clase [MathArray](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)