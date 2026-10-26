---
title: get_TransitionFps()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Pobiera liczbę klatek na sekundę przejścia [frames/sec]. Domyślna wartość to 25.
type: docs
weight: 53
url: /pl/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() metoda


Pobiera liczbę klatek na sekundę przejścia [frames/sec]. Domyślna wartość to 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## Uwagi



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Zobacz także

* Klasa [IGifOptions](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)