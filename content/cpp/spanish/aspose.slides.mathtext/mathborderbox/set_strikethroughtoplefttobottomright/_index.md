---
title: set_StrikethroughTopLeftToBottomRight()
second_title: Referencia de la API de Aspose.Slides para C++
description: Tachado de arriba a la izquierda a abajo a la derecha (el valor predeterminado es false). Especifica el estado oculto o visible de una línea diagonal tachada desde la esquina superior izquierda hasta la esquina inferior derecha de la caja del borde.
type: docs
weight: 209
url: /es/aspose.slides.mathtext/mathborderbox/set_strikethroughtoplefttobottomright/
---
## MathBorderBox::set_StrikethroughTopLeftToBottomRight(bool) method


Strikethrough Top-Left to Bottom-Right (default is false). Specifies the hidden or shown state of a strikethrough diagonal line from the top-left corner to the bottom-right corner of border box.

```cpp
void Aspose::Slides::MathText::MathBorderBox::set_StrikethroughTopLeftToBottomRight(bool value) override
```

## Observaciones


Ejemplo: 
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
borderBox->set_StrikethroughTopLeftToBottomRight(true);
```

## Ver también

* Clase [MathBorderBox](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)