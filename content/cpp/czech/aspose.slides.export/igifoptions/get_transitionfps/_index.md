---
title: get_TransitionFps()
second_title: Aspose.Slides pro C++ API Reference
description: Získá přechodové FPS [frames/sec] Výchozí hodnota je 25.
type: docs
weight: 53
url: /cs/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() metoda


Získá přechodové FPS [frames/sec] Výchozí hodnota je 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## Poznámky



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Viz také

* Třída [IGifOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)