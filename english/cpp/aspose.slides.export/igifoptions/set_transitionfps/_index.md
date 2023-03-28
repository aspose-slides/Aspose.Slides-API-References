---
title: set_TransitionFps()
second_title: Aspose.Slides for C++ API Reference
description: Sets transition FPS [frames/sec] The default value is 25.
type: docs
weight: 66
url: /cpp/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(**int32_t**) method


Sets transition FPS [frames/sec] The default value is 25.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
```

## Remarks



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```




## See Also

* Class [IGifOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)
