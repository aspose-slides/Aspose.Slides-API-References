---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คุณลักษณะนี้ระบุว่าผลกระทบจะทำซ้ำจนกระทั่งคลิกครั้งถัดไปหรือไม่ อ่าน bool.
type: docs
weight: 157
url: /th/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() เมธอด


คุณลักษณะนี้ระบุว่าผลกระทบจะทำซ้ำจนกระทั่งคลิกครั้งถัดไปหรือไม่ อ่าน **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
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

* คลาส [ITiming](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)