---
title: set_RepeatUntilNextClick()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides for C++
description: แอตทริบิวต์นี้ระบุว่าผลกระทบจะทำซ้ำจนกว่าจะคลิกครั้งถัดไปหรือไม่ เขียนเป็น bool.
type: docs
weight: 170
url: /th/aspose.slides.animation/timing/set_repeatuntilnextclick/
---
## Timing::set_RepeatUntilNextClick(bool) เมธอด


แอตทริบิวต์นี้ระบุว่าผลกระทบจะทำซ้ำจนกว่าการคลิกครั้งถัดไปหรือไม่ เขียนเป็น **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_RepeatUntilNextClick(bool value) override
```

## หมายเหตุ


```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// Gets the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// Gets the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Changes effect Timing/Repeat to "Until End of Slide"
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## ดูเพิ่มเติม

* คลาส [Timing](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)