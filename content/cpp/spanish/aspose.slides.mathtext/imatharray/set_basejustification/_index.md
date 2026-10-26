---
title: set_BaseJustification()
second_title: Referencia de API de Aspose.Slides para C++
description: "Especifica la alineación de la matriz respecto al texto circundante. El texto fuera de la matriz puede alinearse con la parte inferior, superior o central de un objeto matriz. Valor predeterminado: Center"
type: docs
weight: 27
url: /es/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) método


Especifica la alineación de la matriz con respecto al texto circundante. El texto fuera de la matriz puede alinearse con la parte inferior, superior o central de un objeto matriz. Valor predeterminado: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
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