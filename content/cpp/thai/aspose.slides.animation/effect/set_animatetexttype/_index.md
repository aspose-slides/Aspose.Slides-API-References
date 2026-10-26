---
title: set_AnimateTextType()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: กำหนดประเภทการเคลื่อนไหวข้อความสำหรับเอฟเฟกต์. ข้อความของรูปร่างสามารถเคลื่อนที่ตามตัวอักษร, ตามคำ หรือทั้งหมดพร้อมกัน. เขียน AnimateTextType.
type: docs
weight: 287
url: /th/aspose.slides.animation/effect/set_animatetexttype/
---
## Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) เมธอด

กำหนดประเภทการเคลื่อนไหวข้อความสำหรับเอฟเฟกต์. ข้อความในรูปร่างสามารถเคลื่อนไหวตามอักษร, ตามคำ หรือทั้งหมดพร้อมกัน. เขียน [AnimateTextType](../../animatetexttype/).

```cpp
void Aspose::Slides::Animation::Effect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value) override
```

## หมายเหตุ


```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## ดูเพิ่มเติม

* Enum [AnimateTextType](../../animatetexttype/)
* คลาส [Effect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* ไลบรารี [Aspose.Slides](../../../)