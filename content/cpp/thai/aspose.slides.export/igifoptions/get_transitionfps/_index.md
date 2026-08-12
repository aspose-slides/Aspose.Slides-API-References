---
title: get_TransitionFps()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: รับค่า FPS ของการเปลี่ยนภาพ [frames/sec] ค่าเริ่มต้นคือ 25.
type: docs
weight: 53
url: /th/aspose.slides.export/igifoptions/get_transitionfps/
---
## IGifOptions::get_TransitionFps() เมธอด

รับค่า FPS ของการเปลี่ยนภาพ [frames/sec] ค่าเริ่มต้นคือ 25.

```cpp
virtual int32_t Aspose::Slides::Export::IGifOptions::get_TransitionFps()=0
```

## หมายเหตุ


```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```


## ดูเพิ่มเติม

* คลาส [IGifOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)