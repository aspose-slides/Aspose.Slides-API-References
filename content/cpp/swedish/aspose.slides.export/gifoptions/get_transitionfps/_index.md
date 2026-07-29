---
title: get_TransitionFps()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar övergångs-FPS [frames/sec] Standardvärdet är 25.
type: docs
weight: 53
url: /sv/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() metod

Hämtar övergångs-FPS [frames/sec]. Standardvärdet är 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## Anmärkningar



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## Se även

* Klass [GifOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)