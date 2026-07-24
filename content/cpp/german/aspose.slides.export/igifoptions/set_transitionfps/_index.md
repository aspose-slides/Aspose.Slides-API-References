---
title: set_TransitionFps()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt die Übergangs-FPS [Frames/Sekunde] Der Standardwert ist 25.
type: docs
weight: 66
url: /de/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) Methode


Setzt die Übergangs-FPS [Frames/Sekunde] Der Standardwert ist 25.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
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