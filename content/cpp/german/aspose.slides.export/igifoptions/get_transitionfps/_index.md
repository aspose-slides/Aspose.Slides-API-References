---
title: get_TransitionFps()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt die Übergangs-FPS [Frames/Sekunde] zurück. Der Standardwert ist 25.
type: docs
weight: 53
url: /de/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() Methode


Gibt die Übergangs-FPS [Frames/Sekunde] zurück. Der Standardwert ist 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## Hinweise



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Siehe auch

* Klasse [IGifOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)