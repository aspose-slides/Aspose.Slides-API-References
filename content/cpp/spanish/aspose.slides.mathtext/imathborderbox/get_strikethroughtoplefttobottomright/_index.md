---
title: get_StrikethroughTopLeftToBottomRight()
second_title: Referencia de API de Aspose.Slides para C++
description: Tachado de la esquina superior izquierda a la esquina inferior derecha (el valor predeterminado es false). Especifica el estado oculto o visible de una línea diagonal tachada desde la esquina superior izquierda hasta la esquina inferior derecha del cuadro del borde.
type: docs
weight: 196
url: /es/aspose.slides.mathtext/imathborderbox/get_strikethroughtoplefttobottomright/
---
## IMathBorderBox::get_StrikethroughTopLeftToBottomRight() método


Tachado de la esquina superior izquierda a la esquina inferior derecha (el valor predeterminado es false). Especifica el estado oculto o visible de una línea diagonal tachada desde la esquina superior izquierda hasta la esquina inferior derecha del cuadro del borde.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughTopLeftToBottomRight()=0
```

## Observaciones


Ejemplo: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughTopLeftToBottomRight(true);
```

## Ver también

* Clase [IMathBorderBox](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)