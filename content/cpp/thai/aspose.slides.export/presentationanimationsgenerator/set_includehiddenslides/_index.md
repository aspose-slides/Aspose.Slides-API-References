---
title: set_IncludeHiddenSlides()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับหรือกำหนดว่าควรรวมสไลด์ที่ซ่อนหรือไม่.
type: docs
weight: 40
url: /th/aspose.slides.export/presentationanimationsgenerator/set_includehiddenslides/
---
## PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool) เมธอด


รับหรือกำหนดว่าควรรวมสไลด์ที่ซ่อนหรือไม่.

```cpp
void Aspose::Slides::Export::PresentationAnimationsGenerator::set_IncludeHiddenSlides(bool value)
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(u"animated.pptx");

auto animationsGenerator = System::MakeObject<PresentationAnimationsGenerator>(presentation->get_SlideSize()->get_Size().ToSize());

animationsGenerator->set_IncludeHiddenSlides(false);
// ...
animationsGenerator->Run(presentation->get_Slides());
```




## ดูเพิ่มเติม

* คลาส [PresentationAnimationsGenerator](../)
* เนมสเปซ [Aspose::Slides::Export](../../)
* ไลบรารี [Aspose.Slides](../../../)