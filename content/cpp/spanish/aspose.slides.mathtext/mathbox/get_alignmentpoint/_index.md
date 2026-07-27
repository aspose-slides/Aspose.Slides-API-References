---
title: get_AlignmentPoint()
second_title: Referencia de API de Aspose.Slides para C++
description: "Cuando es true, este emulador de operador sirve como un punto de alineación; es decir, los puntos de alineación designados en otras ecuaciones pueden alinearse con él. Predeterminado: false"
type: docs
weight: 92
url: /es/aspose.slides.mathtext/mathbox/get_alignmentpoint/
---
## MathBox::get_AlignmentPoint() método


Cuando es true, este emulador de operador sirve como un punto de alineación; es decir, los puntos de alineación designados en otras ecuaciones pueden alinearse con él. Predeterminado: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_AlignmentPoint() override
```

## Observaciones


Ejemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## Ver también

* Clase [MathBox](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)