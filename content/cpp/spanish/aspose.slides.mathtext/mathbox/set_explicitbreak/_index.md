---
title: set_ExplicitBreak()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Explicit break especifica si hay un salto de línea al inicio del objeto Box, de modo que la línea se ajuste al inicio del objeto Box. Especifica el número del operador en la línea anterior de texto matemático que se utilizará como punto de alineación para la línea actual de texto matemático. Valores posibles: 1..255. Predeterminado: 0 (sin salto explícito)"
type: docs
weight: 131
url: /es/aspose.slides.mathtext/mathbox/set_explicitbreak/
---
## MathBox::set_ExplicitBreak(uint8_t) método

Explicit break especifica si hay un salto de línea al comienzo del objeto Box, de modo que la línea se ajuste al inicio del objeto Box. Especifica el número del operador en la línea anterior de texto matemático que se utilizará como punto de alineación para la línea actual de texto matemático. Valores posibles: 1..255. Predeterminado: 0 (sin salto explícito)

```cpp
void Aspose::Slides::MathText::MathBox::set_ExplicitBreak(uint8_t value) override
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