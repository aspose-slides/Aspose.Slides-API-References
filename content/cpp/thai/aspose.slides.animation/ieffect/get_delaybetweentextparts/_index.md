---
title: get_DelayBetweenTextParts()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดความล่าช้าระหว่างส่วนข้อความที่เป็นแอนิเมชัน (คำหรืออักษร) ค่าเป็นบวกระบุเปอร์เซ็นต์ของระยะเวลาเอฟเฟกต์ ค่าเป็นลบระบุความล่าช้าเป็นวินาที อ่าน float.
type: docs
weight: 300
url: /th/aspose.slides.animation/ieffect/get_delaybetweentextparts/
---
## IEffect::get_DelayBetweenTextParts() เมธอด

กำหนดความล่าช้าระหว่างส่วนข้อความที่เป็นแอนิเมชัน (คำหรืออักษร) ค่าเป็นบวกระบุเปอร์เซ็นต์ของระยะเวลาเอฟเฟกต์ ค่าเป็นลบระบุความล่าช้าเป็นวินาที อ่าน **float**.

```cpp
virtual float Aspose::Slides::Animation::IEffect::get_DelayBetweenTextParts()=0
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