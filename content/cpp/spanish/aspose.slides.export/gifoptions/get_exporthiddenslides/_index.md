---
title: get_ExportHiddenSlides()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina si las diapositivas ocultas se exportarán. El valor predeterminado es false.
type: docs
weight: 27
url: /es/aspose.slides.export/gifoptions/get_exporthiddenslides/
---
## GifOptions::get_ExportHiddenSlides() método


Determina si las diapositivas ocultas se exportarán. El valor predeterminado es false.

```cpp
bool Aspose::Slides::Export::GifOptions::get_ExportHiddenSlides() override
```

## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Ver también

* Clase [GifOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)