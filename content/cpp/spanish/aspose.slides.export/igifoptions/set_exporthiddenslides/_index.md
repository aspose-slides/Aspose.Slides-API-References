---
title: set_ExportHiddenSlides()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si las diapositivas ocultas se exportarán. El valor predeterminado es false.
type: docs
weight: 40
url: /es/aspose.slides.export/igifoptions/set_exporthiddenslides/
---
## IGifOptions::set_ExportHiddenSlides(bool) método


Determina si las diapositivas ocultas se exportarán. El valor predeterminado es false.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_ExportHiddenSlides(bool value)=0
```

## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_ExportHiddenSlides(false);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Ver también

* Clase [IGifOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)