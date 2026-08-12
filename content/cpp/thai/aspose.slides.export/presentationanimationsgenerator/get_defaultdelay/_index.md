---
title: get_DefaultDelay()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: รับค่าเวลาหน่วงเริ่มต้น [ms].
type: docs
weight: 1
url: /th/aspose.slides.export/presentationanimationsgenerator/get_defaultdelay/
---
## PresentationAnimationsGenerator::get_DefaultDelay() const เมธอด


รับค่าเวลาหน่วงเวลาเริ่มต้น [ms].

```cpp
int32_t Aspose::Slides::Export::PresentationAnimationsGenerator::get_DefaultDelay() const
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
* เนมสเปส [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)