---
title: get_TransitionFps()
second_title: Aspose.Slides C++ API hivatkozás
description: Lekéri a transition FPS-t [frames/sec]. Az alapértelmezett érték 25.
type: docs
weight: 53
url: /hu/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() method


Lekéri a transition FPS-t [frames/sec]. Az alapértelmezett érték 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## Megjegyzések



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Lásd még

* Osztály [GifOptions](../)
* Névtér [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)