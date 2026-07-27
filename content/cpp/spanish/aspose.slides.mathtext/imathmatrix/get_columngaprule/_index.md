---
title: get_ColumnGapRule()
second_title: Aspose.Slides para C++ Referencia de API
description: "El tipo de espaciado horizontal entre columnas de una matriz; las unidades de espaciado horizontal pueden ser ems o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0)"
type: docs
weight: 105
url: /es/aspose.slides.mathtext/imathmatrix/get_columngaprule/
---
## IMathMatrix::get_ColumnGapRule() método

El tipo de espaciado horizontal entre columnas de una matriz; las unidades de espaciado horizontal pueden ser ems o puntos (almacenados como twips). Predeterminado: SingleSpacingGap (0)

```cpp
virtual MathSpacingRules Aspose::Slides::MathText::IMathMatrix::get_ColumnGapRule()=0
```

## Observaciones

Ejemplo:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_ColumnGapRule(MathSpacingRules::OneAndHalfSpacingGap);
```

## Véase también

* Enumeración [MathSpacingRules](../../mathspacingrules/)
* Clase [IMathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)