---
title: get_TransitionFps()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de overgangs-FPS op [frames/sec]. De standaardwaarde is 25.
type: docs
weight: 53
url: /nl/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() methode


Haalt de overgangs-FPS op [frames/sec]. De standaardwaarde is 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Zie ook

* Klasse [IGifOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)