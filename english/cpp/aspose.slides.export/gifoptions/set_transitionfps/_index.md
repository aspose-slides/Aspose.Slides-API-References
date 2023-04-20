---
title: set_TransitionFps()
second_title: Aspose.Slides for C++ API Reference
description: Sets transition FPS [frames/sec] The default value is 25.
type: docs
weight: 66
url: /cpp/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) method


Sets transition FPS [frames/sec] The default value is 25.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
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