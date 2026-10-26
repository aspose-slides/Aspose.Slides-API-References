---
title: get_BaseJustification()
second_title: Aspose.Slides para C++ Referencia de API
description: "Especifica la justificación vertical con respecto al texto circundante. Los valores posibles son top, bottom y center. Predeterminado: Center"
type: docs
weight: 53
url: /es/aspose.slides.mathtext/mathmatrix/get_basejustification/
---
## MathMatrix::get_BaseJustification() método


Especifica la justificación vertical con respecto al texto circundante. Los valores posibles son top, bottom y center. Predeterminado: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathMatrix::get_BaseJustification() override
```

## Observaciones


Ejemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Ver también

* Enumeración [MathVerticalAlignment](../../mathverticalalignment/)
* Clase [MathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)