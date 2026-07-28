---
title: set_TransitionFps()
second_title: Aspose.Slides dla C++ – odniesienie do API
description: Ustawia przejściowy FPS [frames/sec]. Domyślna wartość to 25.
type: docs
weight: 66
url: /pl/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) metoda


Ustawia przejściowy FPS [frames/sec]. Domyślna wartość to 25.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
```

## Uwagi



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Zobacz także

* Klasa [GifOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)