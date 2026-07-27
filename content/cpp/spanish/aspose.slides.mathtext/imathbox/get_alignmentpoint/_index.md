---
title: get_AlignmentPoint()
second_title: Referencia de API de Aspose.Slides para C++
description: "Cuando es verdadero, este emulador de operador sirve como punto de alineación; es decir, los puntos de alineación designados en otras ecuaciones pueden alinearse con él. Predeterminado: false"
type: docs
weight: 92
url: /es/aspose.slides.mathtext/imathbox/get_alignmentpoint/
---
## IMathBox::get_AlignmentPoint() método


Cuando es verdadero, este emulador de operador sirve como punto de alineación; es decir, los puntos de alineación designados en otras ecuaciones pueden alinearse con él. Predeterminado: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_AlignmentPoint()=0
```

## Observaciones


Ejemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## Ver también

* Clase [IMathBox](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)