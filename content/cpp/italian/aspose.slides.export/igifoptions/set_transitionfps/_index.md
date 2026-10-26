---
title: set_TransitionFps()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta i FPS di transizione [frames/sec]. Il valore predefinito è 25.
type: docs
weight: 66
url: /it/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) metodo

Imposta i FPS di transizione [frames/sec]. Il valore predefinito è 25.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
```

## Osservazioni

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Vedi anche

* Classe [IGifOptions](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Libreria [Aspose.Slides](../../../)