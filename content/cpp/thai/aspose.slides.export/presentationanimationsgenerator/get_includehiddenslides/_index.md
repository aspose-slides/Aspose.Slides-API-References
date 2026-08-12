---
title: get_IncludeHiddenSlides()
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: รับหรือกำหนดว่าควรรวมสไลด์ที่ซ่อนอยู่หรือไม่.
type: docs
weight: 27
url: /th/aspose.slides.export/presentationanimationsgenerator/get_includehiddenslides/
---
## PresentationAnimationsGenerator::get_IncludeHiddenSlides() const เมธอด

รับหรือกำหนดว่าควรรวมสไลด์ที่ซ่อนอยู่หรือไม่

```cpp
bool Aspose::Slides::Export::PresentationAnimationsGenerator::get_IncludeHiddenSlides() const
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

* Class [PresentationAnimationsGenerator](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)