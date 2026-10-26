---
title: set_Rewind()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แอตทริบิวท์นี้ระบุว่าจะรีวินด์เอฟเฟกต์หรือไม่เมื่อเล่นเสร็จแล้ว เขียนเป็น bool.
type: docs
weight: 326
url: /th/aspose.slides.animation/itiming/set_rewind/
---
## ITiming::set_Rewind(bool) เมธอด


แอตทริบิวท์นี้ระบุว่าจะรีวินด์เอฟเฟกต์หรือไม่เมื่อเล่นจบแล้ว เขียนเป็น **bool**.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
```

## หมายเหตุ



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## ดูเพิ่มเติม

* คลาส [ITiming](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)