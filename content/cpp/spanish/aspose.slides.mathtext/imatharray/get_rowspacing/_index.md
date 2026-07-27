---
title: get_RowSpacing()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Espaciado entre filas de una matriz Se usa solo cuando RowSpacingRule está configurado a 3 Exactamente en cuyo caso la unidad de medida es puntos o Multiple en cuyo caso la unidad de medida es media línea. Default: 0"
type: docs
weight: 118
url: /es/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() método


Espaciado entre filas de una matriz Se usa solo cuando RowSpacingRule está configurado a 3 Exactamente en cuyo caso la unidad de medida es puntos o Multiple en cuyo caso la unidad de medida es media línea. Default: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
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