---
title: set_TransitionFps()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Nastaví FPS přechodu [frames/sec]. Výchozí hodnota je 25.
type: docs
weight: 66
url: /cs/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) metoda


Nastaví FPS přechodu [frames/sec]. Výchozí hodnota je 25.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
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