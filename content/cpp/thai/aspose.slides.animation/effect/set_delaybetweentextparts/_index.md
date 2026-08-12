---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดความล่าช้าระหว่างส่วนของข้อความที่เคลื่อนไหว (คำหรืออักษร) ค่าบวกระบุเปอร์เซ็นต์ของระยะเวลาผลกระทบ ค่าลบระบุความล่าช้าเป็นวินาที เขียนเป็น float.
type: docs
weight: 313
url: /th/aspose.slides.animation/effect/set_delaybetweentextparts/
---
## Effect::set_DelayBetweenTextParts(float) เมธอด


กำหนดความล่าช้าระหว่างส่วนของข้อความที่เคลื่อนไหว (คำหรืออักษร) ค่าบวกระบุเปอร์เซ็นต์ของระยะเวลาผลกระทบ ค่าลบระบุความล่าช้าเป็นวินาที เขียนเป็น **float**.

```cpp
void Aspose::Slides::Animation::Effect::set_DelayBetweenTextParts(float value) override
```

## หมายเหตุ



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## ดูเพิ่มเติม

* คลาส [Effect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)