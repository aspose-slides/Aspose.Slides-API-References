---
title: get_AnimateTransitions()
second_title: Referencia de API de Aspose.Slides for C++
description: Devuelve la opción de animación de transiciones. Lectura bool.
type: docs
weight: 1
url: /es/aspose.slides.export/html5options/get_animatetransitions/
---
## Html5Options::get_AnimateTransitions() método


Devuelve la opción de animación de transiciones. Lectura **bool**.

```cpp
bool Aspose::Slides::Export::Html5Options::get_AnimateTransitions() override
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

* Clase [Html5Options](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)