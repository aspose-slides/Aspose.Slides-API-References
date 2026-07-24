---
title: set_TransitionFps()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt die Übergangs-FPS [frames/sec]. Der Standardwert ist 25.
type: docs
weight: 66
url: /de/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) Methode

Setzt die Übergangs-FPS [frames/sec]. Der Standardwert ist 25.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
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