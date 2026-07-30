---
title: get_TransitionFps()
second_title: Aspose.Slides per C++ Riferimento API
description: Restituisce i FPS di transizione [fotogrammi/sec] Il valore predefinito è 25.
type: docs
weight: 53
url: /it/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() metodo


Restituisce i FPS di transizione [fotogrammi/sec]. Il valore predefinito è 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
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