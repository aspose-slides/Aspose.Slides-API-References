---
title: set_BaseJustification()
second_title: Referencia de API de Aspose.Slides para C++
description: "Especifica la justificación vertical respecto al texto circundante. Los valores posibles son top, bottom y center. Predeterminado: Center"
type: docs
weight: 66
url: /es/aspose.slides.mathtext/mathmatrix/set_basejustification/
---
## MathMatrix::set_BaseJustification(MathVerticalAlignment) método

Especifica la justificación vertical respecto al texto circundante. Los valores posibles son top, bottom y center. Predeterminado: Center

```cpp
void Aspose::Slides::MathText::MathMatrix::set_BaseJustification(MathVerticalAlignment value) override
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