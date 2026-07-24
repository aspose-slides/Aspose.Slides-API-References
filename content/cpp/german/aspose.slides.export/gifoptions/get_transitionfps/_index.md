---
title: get_TransitionFps()
second_title: Aspose.Slides für C++ API Referenz
description: Ermittelt die Übergangs-FPS [frames/sec]. Der Standardwert ist 25.
type: docs
weight: 53
url: /de/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() Methode


Ermittelt die Übergangs-FPS [frames/sec]. Der Standardwert ist 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## Hinweise



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Siehe auch

* Klasse [GifOptions](../)
* Namensraum [Aspose::Slides::Export](../../)
* Bibliothek [Aspose.Slides](../../../)