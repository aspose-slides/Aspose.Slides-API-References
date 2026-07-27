---
title: set_AnimateShapes()
second_title: Referencia de API de Aspose.Slides para C++
description: Establece la opción de animación de formas. Escriba bool.
type: docs
weight: 40
url: /es/aspose.slides.export/ihtml5options/set_animateshapes/
---
## IHtml5Options::set_AnimateShapes(bool) método


Establece la opción de animación de formas. Escriba **bool**.

```cpp
virtual void Aspose::Slides::Export::IHtml5Options::set_AnimateShapes(bool value)=0
```

## Observaciones


Ejemplo: 
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateShapes(true);

pres->Save(u"demo-animate-shapes.html", SaveFormat::Html5, options);
```




## Ver también

* Clase [IHtml5Options](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)