---
title: set_DefaultDelay()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดเวลาเดเลย์เริ่มต้นเป็น [ms].
type: docs
weight: 14
url: /th/aspose.slides.export/presentationanimationsgenerator/set_defaultdelay/
---
## PresentationAnimationsGenerator::set_DefaultDelay(int32_t) เมธอด


กำหนดเวลาเดเลย์เริ่มต้นเป็น [ms].

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_DefaultDelay(int32_t value)
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_DefaultDelay(1000); // 1s
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## ดูเพิ่มเติม

* คลาส [PresentationAnimationsGenerator](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)