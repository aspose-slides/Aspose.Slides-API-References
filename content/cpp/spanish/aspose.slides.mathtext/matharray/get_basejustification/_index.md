---
title: get_BaseJustification()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Especifica la alineación de la matriz respecto al texto circundante. El texto fuera de la matriz puede alinearse con la bottom, la top o la center de un objeto matriz. Valor predeterminado: Center"
type: docs
weight: 14
url: /es/aspose.slides.mathtext/matharray/get_basejustification/
---
## MathArray::get_BaseJustification() método

Especifica la alineación de la matriz respecto al texto circundante. El texto fuera de la matriz puede alinearse con la bottom, la top o la center de un objeto matriz. Valor predeterminado: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathArray::get_BaseJustification() override
```

## Observaciones

Ejemplo: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Ver también

* Enumeración [MathVerticalAlignment](../../mathverticalalignment/)
* Clase [MathArray](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)