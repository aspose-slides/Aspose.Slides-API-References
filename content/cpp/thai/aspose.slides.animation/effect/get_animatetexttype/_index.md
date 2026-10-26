---
title: get_AnimateTextType()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: กำหนดประเภทข้อความเคลื่อนไหวสำหรับเอฟเฟกต์ ข้อความรูปทรงสามารถเคลื่อนไหวได้ตามตัวอักษร, ตามคำ หรือทั้งหมดพร้อมกัน. อ่าน AnimateTextType.
type: docs
weight: 274
url: /th/aspose.slides.animation/effect/get_animatetexttype/
---
## Effect::get_AnimateTextType() เมธอด

กำหนดประเภทข้อความเคลื่อนไหวสำหรับเอฟเฟกต์ ข้อความรูปทรงสามารถเคลื่อนไหวได้ตามตัวอักษร, ตามคำ หรือทั้งหมดพร้อมกัน. อ่าน [AnimateTextType](../../animatetexttype/).

```cpp
Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::Effect::get_AnimateTextType() override
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
* Library [Aspose.Slides](../../../)