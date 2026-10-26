---
title: get_BaseJustification()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Especifica la alineación de la matriz con respecto al texto circundante. El texto fuera de la matriz puede alinearse con la parte inferior, superior o el centro de un objeto matriz. Valor predeterminado: Center"
type: docs
weight: 14
url: /es/aspose.slides.mathtext/imatharray/get_basejustification/
---
## IMathArray::get_BaseJustification() método


Especifica la alineación de la matriz con respecto al texto circundante. El texto fuera de la matriz puede alinearse con la parte inferior, superior o el centro de un objeto matriz. Valor predeterminado: Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathArray::get_BaseJustification()=0
```

## Observaciones


Ejemplo: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Ver también

* Enumeración [MathVerticalAlignment](../../mathverticalalignment/)
* Clase [IMathArray](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)