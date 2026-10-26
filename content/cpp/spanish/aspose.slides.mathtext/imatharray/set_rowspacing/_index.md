---
title: set_RowSpacing()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Espaciado entre filas de una matriz Se usa solo cuando RowSpacingRule está establecido en 3 Exactamente en cuyo caso la unidad de medida es puntos o Multiple en cuyo caso la unidad de medida es media-líneas. Predeterminado: 0"
type: docs
weight: 131
url: /es/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) método

Espaciado entre filas de una matriz Se usa solo cuando RowSpacingRule está establecido en 3 Exactamente en cuyo caso la unidad de medida es puntos o Multiple en cuyo caso la unidad de medida es media-líneas. Predeterminado: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
```

## Observaciones


Ejemplo: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## Ver también

* Clase [IMathArray](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)