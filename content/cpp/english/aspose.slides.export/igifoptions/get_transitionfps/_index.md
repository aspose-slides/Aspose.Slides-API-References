---
title: get_TransitionFps()
second_title: Aspose.Slides for C++ API Reference
description: Gets transition FPS [frames/sec] The default value is 25.
type: docs
weight: 53
url: /aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() method


Gets transition FPS [frames/sec] The default value is 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
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