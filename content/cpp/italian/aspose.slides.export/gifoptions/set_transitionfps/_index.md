---
title: set_TransitionFps()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta i FPS di transizione [fotogrammi/sec] Il valore predefinito è 25.
type: docs
weight: 66
url: /it/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) metodo


Imposta i FPS di transizione [fotogrammi/sec] Il valore predefinito è 25.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
```

## Osservazioni



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