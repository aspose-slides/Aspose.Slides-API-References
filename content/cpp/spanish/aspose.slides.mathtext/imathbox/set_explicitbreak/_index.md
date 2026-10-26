---
title: set_ExplicitBreak()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Explicit break indica si hay un salto de línea al inicio del objeto Box, de modo que la línea se ajuste al inicio del objeto Box. Especifica el número del operador en la línea anterior de texto matemático que se debe usar como punto de alineación para la línea actual de texto matemático valores posibles: 1..255 Predeterminado: 0 (no explicit break)"
type: docs
weight: 131
url: /es/aspose.slides.mathtext/imathbox/set_explicitbreak/
---
## IMathBox::set_ExplicitBreak(uint8_t) método

Explicit break especifica si hay un salto de línea al inicio del objeto Box, de modo que la línea se ajuste al inicio del objeto box. Especifica el número del operador en la línea anterior de texto matemático que se debe usar como punto de alineación para la línea actual de texto matemático valores posibles: 1..255 Predeterminado: 0 (no explicit break)

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_ExplicitBreak(uint8_t value)=0
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