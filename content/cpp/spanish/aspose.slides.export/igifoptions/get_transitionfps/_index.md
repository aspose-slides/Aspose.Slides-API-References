---
title: get_TransitionFps()
second_title: Referencia de la API de Aspose.Slides para C++
description: Obtiene FPS de transición [frames/sec] El valor predeterminado es 25.
type: docs
weight: 53
url: /es/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() método

Obtiene FPS de transición [frames/sec] El valor predeterminado es 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## Observaciones


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```


## Ver también

* Clase [IGifOptions](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)