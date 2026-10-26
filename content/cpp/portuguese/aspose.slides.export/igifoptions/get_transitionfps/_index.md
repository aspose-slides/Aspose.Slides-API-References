---
title: get_TransitionFps()
second_title: Referência da API Aspose.Slides para C++
description: Obtém FPS de transição [frames/seg] O valor padrão é 25.
type: docs
weight: 53
url: /pt/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() método


Obtém FPS de transição [frames/sec] O valor padrão é 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Veja Também

* Classe [IGifOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)