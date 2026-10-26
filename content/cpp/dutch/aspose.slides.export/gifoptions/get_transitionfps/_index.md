---
title: get_TransitionFps()
second_title: Aspose.Slides voor de C++ API-referentie
description: Haalt overgang FPS op [frames/sec] De standaardwaarde is 25.
type: docs
weight: 53
url: /nl/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() methode


Haalt de overgang FPS op [frames/sec] De standaardwaarde is 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## Opmerkingen



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Zie ook

* Klasse [GifOptions](../)
* Naamruimte [Aspose::Slides::Export](../../)
* Bibliotheek [Aspose.Slides](../../../)