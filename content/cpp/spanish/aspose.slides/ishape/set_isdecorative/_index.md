---
title: set_IsDecorative()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece la opción 'Mark as decorative' Lectura/escritura **bool**.
type: docs
weight: 417
url: /es/aspose.slides/ishape/set_isdecorative/
---
## IShape::set_IsDecorative(bool) método


Establece la opción 'Mark as decorative' Lectura/escritura **bool**.

```cpp
virtual void Aspose::Slides::IShape::set_IsDecorative(bool value)=0
```

## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>(u"sample.pptx")
pres->get_Slide(0)->get_Shape(0)->set_IsDecorative(true);
```

## Ver también

* Clase [IShape](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)