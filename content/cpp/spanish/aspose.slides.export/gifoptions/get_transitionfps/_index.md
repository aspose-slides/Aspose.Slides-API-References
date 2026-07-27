---
title: get_TransitionFps()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene los FPS de transición [frames/sec]. El valor predeterminado es 25.
type: docs
weight: 53
url: /es/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() método

Obtiene los FPS de transición [frames/sec]. El valor predeterminado es 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
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