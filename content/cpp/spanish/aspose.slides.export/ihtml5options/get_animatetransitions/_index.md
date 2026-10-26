---
title: get_AnimateTransitions()
second_title: Aspose.Slides para C++ Referencia de API
description: Devuelve la opción de animación de transiciones. Solo lectura bool.
type: docs
weight: 1
url: /es/aspose.slides.export/ihtml5options/get_animatetransitions/
---
## IHtml5Options::get_AnimateTransitions() método


Devuelve la opción de animación de transiciones. Solo lectura **bool**.

```cpp
virtual bool Aspose::Slides::Export::IHtml5Options::get_AnimateTransitions()=0
```

## Observaciones


Ejemplo:
```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");

auto options = System::MakeObject<Html5Options>();
options->set_AnimateTransitions(true);

pres->Save(u"demo-animate-transitions.html", SaveFormat::Html5, options);
```




## Véase también

* Clase [IHtml5Options](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)