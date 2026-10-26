---
title: set_TransitionFps()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: ตั้งค่า FPS ของการเปลี่ยนภาพ [เฟรม/วินาที] ค่าเริ่มต้นคือ 25.
type: docs
weight: 66
url: /th/aspose.slides.export/gifoptions/set_transitionfps/
---
## GifOptions::set_TransitionFps(int32_t) เมธอด


ตั้งค่า FPS ของการเปลี่ยนภาพ [เฟรม/วินาที] ค่าเริ่มต้นคือ 25.

```cpp
void Aspose::Slides::Export::GifOptions::set_TransitionFps(int32_t value) override
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