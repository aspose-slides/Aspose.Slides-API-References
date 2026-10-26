---
title: get_TransitionFps()
second_title: Referência da API Aspose.Slides para C++
description: Obtém FPS de transição [frames/seg] O valor padrão é 25.
type: docs
weight: 53
url: /pt/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() método

Obtém FPS de transição [frames/sec]. O valor padrão é 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Ver também

* Classe [GifOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)