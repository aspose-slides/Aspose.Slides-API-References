---
title: set_TransitionFps()
second_title: Referencia de la API de Aspose.Slides para C++
description: Establece los FPS de transición [fotogramas/seg] El valor predeterminado es 25.
type: docs
weight: 66
url: /es/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) método


Establece los FPS de transición [fotogramas/seg] El valor predeterminado es 25.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
```

## Observaciones



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Ver también

* Clase [GifOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)