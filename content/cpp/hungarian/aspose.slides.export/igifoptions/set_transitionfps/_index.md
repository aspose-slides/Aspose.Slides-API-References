---
title: set_TransitionFps()
second_title: Aspose.Slides C++ API Referenciája
description: Beállítja az átmeneti FPS-t [képkocka/mp] Az alapértelmezett érték 25.
type: docs
weight: 66
url: /hu/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) metódus


Beállítja az átmeneti FPS-t [képkocka/mp] Az alapértelmezett érték 25.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
```

## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Lásd még

* Osztály [IGifOptions](../)
* Névtere [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)