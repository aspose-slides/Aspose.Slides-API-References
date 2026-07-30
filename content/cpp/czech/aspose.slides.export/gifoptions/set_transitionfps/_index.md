---
title: set_TransitionFps()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastavuje FPS přechodu [snímků/s] Výchozí hodnota je 25.
type: docs
weight: 66
url: /cs/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) metoda


Nastavuje FPS přechodu [snímků/s] Výchozí hodnota je 25.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
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