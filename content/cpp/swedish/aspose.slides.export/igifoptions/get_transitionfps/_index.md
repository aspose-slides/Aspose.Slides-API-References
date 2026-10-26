---
title: get_TransitionFps()
second_title: Aspose.Slides för C++ API-referens
description: Hämtar övergång FPS [frames/sec] Standardvärdet är 25.
type: docs
weight: 53
url: /sv/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() metod


Hämtar övergång FPS [frames/sec] Standardvärdet är 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## Anmärkningar



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## Se även

* Klass [IGifOptions](../)
* Namnrymd [Aspose::Slides::Export](../../)
* Bibliotek [Aspose.Slides](../../../)