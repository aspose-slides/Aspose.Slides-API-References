---
title: get_ExplicitBreak()
second_title: Aspose.Slides para la referencia de la API de C++
description: "Explicit break especifica si hay un salto de línea al inicio del objeto Box, de modo que la línea se envuelva al inicio del objeto box. Especifica el número del operador en la línea anterior del texto matemático que se utilizará como punto de alineación para la línea actual del texto matemático valores posibles: 1..255 Predeterminado: 0 (sin salto explícito)"
type: docs
weight: 118
url: /es/aspose.slides.mathtext/imathbox/get_explicitbreak/
---
## IMathBox::get_ExplicitBreak() método

Explicit break especifica si hay un salto de línea al inicio del objeto Box, de modo que la línea se envuelva al inicio del objeto Box. Especifica el número del operador en la línea anterior del texto matemático que se usará como punto de alineación para la línea actual del texto matemático valores posibles: 1..255 Predeterminado: 0 (sin salto explícito)

```cpp
virtual uint8_t Aspose::Slides::MathText::IMathBox::get_ExplicitBreak()=0
```

## Observaciones

Ejemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Ver también

* Clase [IMathBox](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)