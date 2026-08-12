---
title: set_RepeatUntilNextClick()
second_title: Aspose.Slides for C++ เอกสารอ้างอิง API
description: คุณลักษณะนี้ระบุว่าผลกระทบจะทำซ้ำจนกว่าจะคลิกครั้งถัดไปหรือไม่ เขียนเป็น bool.
type: docs
weight: 170
url: /th/aspose.slides.animation/itiming/set_repeatuntilnextclick/
---
## ITiming::set_RepeatUntilNextClick(bool) เมธอด


คุณลักษณะนี้ระบุว่าผลกระทบจะทำซ้ำจนกว่าจะคลิกครั้งถัดไปหรือไม่ เขียนเป็น **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilNextClick(bool value)=0
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

## ดูเพิ่ม

* คลาส [ITiming](../)
* เนมสเปส [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)