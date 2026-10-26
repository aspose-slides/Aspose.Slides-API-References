---
title: set_BaseJustification()
second_title: Referencia de API de Aspose.Slides para C++
description: "Especifica la justificación vertical respecto al texto circundante. Los valores posibles son top, bottom y center. Predeterminado: Center"
type: docs
weight: 66
url: /es/aspose.slides.mathtext/imathmatrix/set_basejustification/
---
## IMathMatrix::set_BaseJustification(MathVerticalAlignment) método


Especifica la justificación vertical respecto al texto circundante. Los valores posibles son top, bottom y center. Predeterminado: Center

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_BaseJustification(MathVerticalAlignment value)=0
```

## Observaciones


Ejemplo: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## Ver también

* Enumeración [MathVerticalAlignment](../../mathverticalalignment/)
* Clase [IMathMatrix](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)