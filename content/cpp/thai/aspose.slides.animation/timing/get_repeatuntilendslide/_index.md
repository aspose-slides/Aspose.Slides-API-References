---
title: get_RepeatUntilEndSlide()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แอตทริบิวต์นี้ระบุว่าผลกระทบจะทำซ้ำจนถึงจบสไลด์หรือไม่ อ่าน bool.
type: docs
weight: 131
url: /th/aspose.slides.animation/timing/get_repeatuntilendslide/
---
## Timing::get_RepeatUntilEndSlide() เมธอด

แอตทริบิวต์นี้ระบุว่าผลกระทบจะทำซ้ำจนถึงจบสไลด์หรือไม่ อ่าน **bool**.

```cpp
bool Aspose::Slides::Animation::Timing::get_RepeatUntilEndSlide() override
```

## หมายเหตุ

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## ดูเพิ่มเติม

* คลาส [Timing](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)