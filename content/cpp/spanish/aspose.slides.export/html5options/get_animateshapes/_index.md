---
title: get_AnimateShapes()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve la opción de animación de formas. Lectura bool.
type: docs
weight: 27
url: /es/aspose.slides.export/html5options/get_animateshapes/
---
## Html5Options::get_AnimateShapes() método


Devuelve la opción de animación de formas. Lectura **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateShapes() override
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

* Clase [Html5Options](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)