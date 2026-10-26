---
title: AddEffect()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เพิ่มเอฟเฟกต์ใหม่ไปยังจุดสิ้นสุดของลำดับปัจจุบันของการเคลื่อนไหวข้อความในกลุ่ม เท่านั้นจะใช้ได้หากจำนวนย่อหน้าข้อความเท่ากับหรือมากกว่าจำนวนเอฟเฟกต์ของกลุ่มนี้!
type: docs
weight: 53
url: /th/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) เมธอด

เพิ่มเอฟเฟกต์ใหม่ไปยังจุดสิ้นสุดของลำดับปัจจุบันของการเคลื่อนไหวข้อความในกลุ่ม เท่านั้นจะใช้ได้หากจำนวนย่อหน้าข้อความเท่ากับหรือมากกว่าจำนวนเอฟเฟกต์ของกลุ่มนี้!

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Type of an animation effect [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Subtypes of animation effect [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Trigger type of effect [EffectTriggerType](../../effecttriggertype/) |

### ค่าที่ส่งกลับ

New effect object [IEffect](../../ieffect/)

## ดูเพิ่มเติม

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* คลาส [IEffect](../../ieffect/)
* คลาส [TextAnimation](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)