---
title: get_TransitionFps()
second_title: Aspose.Slides for C++ API Reference
description: Gets transition FPS [frames/sec] The default value is 25.
type: docs
weight: 53
url: /cpp/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() method


Gets transition FPS [frames/sec] The default value is 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## Remarks



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## See Also

* Class [GifOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)
