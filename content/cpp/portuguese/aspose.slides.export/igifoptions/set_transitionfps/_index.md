---
title: set_TransitionFps()
second_title: Referência da API Aspose.Slides para C++
description: Define o FPS da transição [frames/seg] O valor padrão é 25.
type: docs
weight: 66
url: /pt/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) método


Define o FPS da transição [frames/seg] O valor padrão é 25.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
```

## Observações



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Ver também

* Classe [IGifOptions](../)
* Espaço de nomes [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)