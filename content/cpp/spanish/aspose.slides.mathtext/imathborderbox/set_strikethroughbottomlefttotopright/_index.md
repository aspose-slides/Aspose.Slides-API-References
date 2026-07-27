---
title: set_StrikethroughBottomLeftToTopRight()
second_title: Referencia de API de Aspose.Slides para C++
description: Tachado de la esquina inferior izquierda a la superior derecha (el valor predeterminado es false). Especifica el estado oculto o visible de una línea diagonal de tachado desde la esquina inferior izquierda hasta la esquina superior derecha de la caja de borde.
type: docs
weight: 183
url: /es/aspose.slides.mathtext/imathborderbox/set_strikethroughbottomlefttotopright/
---
## IMathBorderBox::set_StrikethroughBottomLeftToTopRight(bool) method


Strikethrough Bottom-Left to Top-Right (el valor predeterminado es false). Especifica el estado oculto o visible de una línea diagonal de tachado desde la esquina inferior izquierda hasta la esquina superior derecha de la caja de borde.

```cpp
virtual void Aspose::Slides::MathText::IMathBorderBox::set_StrikethroughBottomLeftToTopRight(bool value)=0
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