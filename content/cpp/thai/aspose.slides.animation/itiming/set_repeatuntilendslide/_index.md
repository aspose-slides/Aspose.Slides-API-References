---
title: set_RepeatUntilEndSlide()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: คุณลักษณะนี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนกระทั่งจบสไลด์หรือไม่ เขียน bool.
type: docs
weight: 144
url: /th/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITiming::set_RepeatUntilEndSlide(bool) เมธอด


คุณลักษณะนี้ระบุว่าเอฟเฟกต์จะทำซ้ำจนกระทั่งจบสไลด์หรือไม่ เขียน **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
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

* คลาส [ITiming](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)