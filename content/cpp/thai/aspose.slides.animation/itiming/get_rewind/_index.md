---
title: get_Rewind()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คุณลักษณะนี้ระบุว่าผลกระทบจะย้อนกลับเมื่อเล่นเสร็จหรือไม่ อ่าน bool.
type: docs
weight: 313
url: /th/aspose.slides.animation/itiming/get_rewind/
---
## ITTiming::get_Rewind() เมธอด


คุณลักษณะนี้ระบุว่าผลกระทบจะย้อนกลับเมื่อเล่นเสร็จหรือไม่. อ่าน **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
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