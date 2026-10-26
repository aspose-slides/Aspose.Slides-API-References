---
title: set_TransitionFps()
second_title: Aspose.Slides สำหรับเอกสารอ้างอิง API ของ C++
description: กำหนด FPS ของการเปลี่ยนภาพ [frames/sec] ค่าเริ่มต้นคือ 25.
type: docs
weight: 66
url: /th/aspose.slides.export/igifoptions/set_transitionfps/
---
## IGifOptions::set_TransitionFps(int32_t) เมธอด

กำหนด FPS ของการเปลี่ยนภาพ [เฟรม/วินาที] ค่าเริ่มต้นคือ 25.

```cpp
virtual void Aspose::Slides::Export::IGifOptions::set_TransitionFps(int32_t value)=0
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