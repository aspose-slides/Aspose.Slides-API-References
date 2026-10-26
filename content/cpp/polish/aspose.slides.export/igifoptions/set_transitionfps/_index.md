---
title: set_TransitionFps()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Ustawia przejściowe FPS [klatki/s]. Domyślna wartość to 25.
type: docs
weight: 66
url: /pl/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) method


Ustawia liczbę klatek na sekundę przejścia [klatek/s] Domyślna wartość to 25.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
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