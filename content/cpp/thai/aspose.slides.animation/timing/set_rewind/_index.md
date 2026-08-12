---
title: set_Rewind()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คุณลักษณะนี้ระบุว่าผลกระทบจะถอยกลับเมื่อการเล่นเสร็จสิ้น เขียน bool.
type: docs
weight: 248
url: /th/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) เมธอด


คุณลักษณะนี้ระบุว่าผลกระทบจะถอยกลับเมื่อการเล่นเสร็จสิ้น เขียน **bool**.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
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

* คลาส [Timing](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)