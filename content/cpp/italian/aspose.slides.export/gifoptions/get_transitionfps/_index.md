---
title: get_TransitionFps()
second_title: Riferimento API di Aspose.Slides per C++
description: Ottiene i FPS di transizione [frame/sec] Il valore predefinito è 25.
type: docs
weight: 53
url: /it/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() metodo

Ottiene i FPS di transizione [frame/sec] Il valore predefinito è 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## Note

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Vedi anche

* Classe [GifOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)