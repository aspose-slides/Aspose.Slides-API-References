---
title: set_TransitionFps()
second_title: Referência da API Aspose.Slides para C++
description: Define o FPS de transição [frames/seg] O valor padrão é 25.
type: docs
weight: 66
url: /pt/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) método


Define o FPS de transição [frames/seg] O valor padrão é 25.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Veja Também

* Classe [GifOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)