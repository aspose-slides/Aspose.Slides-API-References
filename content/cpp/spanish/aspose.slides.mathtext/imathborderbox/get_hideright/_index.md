---
title: get_HideRight()
second_title: Referencia de API de Aspose.Slides para C++
description: Ocultar borde derecho (el valor predeterminado es false) - especifica el estado oculto o visible del borde derecho de la caja de borde.
type: docs
weight: 92
url: /es/aspose.slides.mathtext/imathborderbox/get_hideright/
---
## IMathBorderBox::get_HideRight() método

Ocultar borde derecho (valor predeterminado es false) - especifica el estado oculto o visible del borde derecho de la caja de borde.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideRight()=0
```

## Observaciones

Ejemplo:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideRight(true);
```

## Ver también

* Clase [IMathBorderBox](../)
* Espacio de nombres [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)