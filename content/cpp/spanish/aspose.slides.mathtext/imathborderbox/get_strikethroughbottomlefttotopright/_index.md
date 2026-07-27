---
title: get_StrikethroughBottomLeftToTopRight()
second_title: Referencia de API de Aspose.Slides para C++
description: Tachado de la esquina inferior izquierda a la superior derecha (el valor predeterminado es false). Especifica el estado oculto o visible de una línea diagonal tachada desde la esquina inferior izquierda hasta la esquina superior derecha del cuadro de borde.
type: docs
weight: 170
url: /es/aspose.slides.mathtext/imathborderbox/get_strikethroughbottomlefttotopright/
---
## IMathBorderBox::get_StrikethroughBottomLeftToTopRight() método


Tachado de la esquina inferior izquierda a la superior derecha (el valor predeterminado es false). Especifica el estado oculto o visible de una línea diagonal tachada desde la esquina inferior izquierda hasta la esquina superior derecha del cuadro de borde.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughBottomLeftToTopRight()=0
```

## Observaciones


Ejemplo: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```

## Ver también

* Clase [IMathBorderBox](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)