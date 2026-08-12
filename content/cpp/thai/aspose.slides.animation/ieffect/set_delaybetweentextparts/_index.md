---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดความหน่วงระหว่างส่วนของข้อความที่เคลื่อนไหว (คำหรืออักษร) ค่าเป็นบวกระบุเปอร์เซ็นต์ของระยะเวลาเอฟเฟกต์ ค่าเป็นลบระบุความหน่วงเป็นวินาที เขียน float.
type: docs
weight: 313
url: /th/aspose.slides.animation/ieffect/set_delaybetweentextparts/
---
## IEffect::set_DelayBetweenTextParts(float) เมธอด


กำหนดความหน่วงระหว่างส่วนของข้อความที่เคลื่อนไหว (คำหรืออักษร) ค่าบวกระบุเปอร์เซ็นต์ของระยะเวลาเอฟเฟกต์ ค่าลบระบุความหน่วงเป็นวินาที เขียนเป็น **float**.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_DelayBetweenTextParts(float value)=0
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

* คลาส [IEffect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)