---
title: get_TransitionFps()
second_title: Aspose.Slides dla C++ Referencja API
description: Pobiera liczbę klatek na sekundę przejścia [frames/sec]. Domyślna wartość to 25.
type: docs
weight: 53
url: /pl/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() metoda

Pobiera liczbę klatek na sekundę przejścia [frames/sec]. Domyślna wartość to 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
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