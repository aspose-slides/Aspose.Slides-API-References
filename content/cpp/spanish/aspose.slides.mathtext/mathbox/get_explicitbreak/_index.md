---
title: get_ExplicitBreak()
second_title: Referencia de API de Aspose.Slides para C++
description: "El salto explícito indica si hay un salto de línea al inicio del objeto Box, de modo que la línea se ajuste al comienzo del objeto box. Especifica el número del operador en la línea anterior del texto matemático que se debe usar como punto de alineación para la línea actual del texto matemático. Valores posibles: 1..255 Predeterminado: 0 (sin salto explícito)"
type: docs
weight: 118
url: /es/aspose.slides.mathtext/mathbox/get_explicitbreak/
---
## MathBox::get_ExplicitBreak() método


El salto explícito indica si hay un salto de línea al comienzo del objeto Box, de modo que la línea se envuelve al iniciar el objeto Box. Especifica el número del operador en la línea anterior del texto matemático que se utilizará como punto de alineación para la línea actual del texto matemático. Valores posibles: 1..255 Predeterminado: 0 (sin salto explícito)

```cpp
uint8_t Aspose::Slides::MathText::MathBox::get_ExplicitBreak() override
```

## Observaciones


Ejemplo: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_ExplicitBreak(1);
```

## Ver también

* Clase [MathBox](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)