---
title: get_DelayBetweenTextParts()
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดความหน่วงระหว่างส่วนข้อความที่เคลื่อนไหว (คำหรืออักษร) ค่าบวกระบุเปอร์เซ็นต์ของระยะเวลากิจกรรม ค่าลบระบุความหน่วงเป็นวินาที อ่าน float.
type: docs
weight: 300
url: /th/aspose.slides.animation/effect/get_delaybetweentextparts/
---
## Effect::get_DelayBetweenTextParts() เมธอด


กำหนดความหน่วงระหว่างส่วนข้อความที่เคลื่อนไหว (คำหรืออักษร). ค่าบวกระบุเปอร์เซ็นต์ของระยะเวลากิจกรรม. ค่าลบระบุความหน่วงเป็นวินาที. อ่าน **float**.

```cpp
float Aspose::Slides::Animation::Effect::get_DelayBetweenTextParts() override
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