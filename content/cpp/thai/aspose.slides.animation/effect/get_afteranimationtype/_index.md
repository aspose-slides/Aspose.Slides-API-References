---
title: get_AfterAnimationType()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: กำหนดประเภทการเคลื่อนไหวหลังสำหรับเอฟเฟกต์. อ่าน AfterAnimationType.
type: docs
weight: 222
url: /th/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() เมธอด


กำหนดประเภทของการเคลื่อนไหวหลังสำหรับเอฟเฟกต์. อ่าน [AfterAnimationType](../../afteranimationtype/).

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## ดูเพิ่มเติม

* Enum [AfterAnimationType](../../afteranimationtype/)
* คลาส [Effect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)