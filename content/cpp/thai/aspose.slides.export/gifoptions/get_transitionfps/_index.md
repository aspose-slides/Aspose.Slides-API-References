---
title: get_TransitionFps()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: รับค่า FPS ของการเปลี่ยนแปลง [frames/sec] ค่าเริ่มต้นคือ 25.
type: docs
weight: 53
url: /th/aspose.slides.export/gifoptions/get_transitionfps/
---
## GifOptions::get_TransitionFps() เมธอด


รับค่า FPS ของการเปลี่ยนแปลง [frames/sec] ค่าเริ่มต้นคือ 25.

```cpp
int32_t Aspose::Slides::Export::GifOptions::get_TransitionFps() override
```

## หมายเหตุ



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

auto gifOptions = System::MakeObject<GifOptions>();
gifOptions->set_TransitionFps(60);
pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## ดูเพิ่มเติม

* คลาส [GifOptions](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)