---
title: get_TransitionFps()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Získá přechodové FPS [frames/sec] Výchozí hodnota je 25.
type: docs
weight: 53
url: /cs/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() metoda


Získá přechodové FPS [frames/sec] Výchozí hodnota je 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## Poznámky



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Viz také

* Třída [GifOptions](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)