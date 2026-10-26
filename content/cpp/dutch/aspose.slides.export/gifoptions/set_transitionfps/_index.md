---
title: set_TransitionFps()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt de overgang-FPS [frames/sec] in. De standaardwaarde is 25.
type: docs
weight: 66
url: /nl/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) methode

Stelt de overgang-FPS [frames/sec] in. De standaardwaarde is 25.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
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
* Library [Aspose.Slides](../../../)