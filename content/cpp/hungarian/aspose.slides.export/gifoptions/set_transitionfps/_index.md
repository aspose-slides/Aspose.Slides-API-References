---
title: set_TransitionFps()
second_title: Aspose.Slides for C++ API Referencia
description: Beállítja az átmenet FPS-ét [frames/sec] Az alapértelmezett érték 25.
type: docs
weight: 66
url: /hu/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) metódus


Beállítja az átmenet FPS-ét [frames/sec] Az alapértelmezett érték 25.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
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
* Névtere [Aspose::Slides::Export](../../)
* Könyvtár [Aspose.Slides](../../../)