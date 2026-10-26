---
title: set_AnimateTextType()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดประเภทการเคลื่อนไหวของข้อความสำหรับเอฟเฟกต์ ข้อความรูปทรงสามารถเคลื่อนไหวได้ตามตัวอักษร ตามคำ หรือทั้งหมดพร้อมกัน เขียน AnimateTextType.
type: docs
weight: 287
url: /th/aspose.slides.animation/ieffect/set_animatetexttype/
---
## IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType) เมธอด

กำหนดประเภทการทำให้ข้อความเคลื่อนไหวสำหรับเอฟเฟกต์ ข้อความในรูปร่างสามารถทำให้เคลื่อนไหวได้ตามตัวอักษร ตามคำ หรือทั้งหมดพร้อมกัน เขียน [AnimateTextType](../../animatetexttype/).

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AnimateTextType(Aspose::Slides::Animation::AnimateTextType value)=0
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
* คลาส [IEffect](../)
* เนมสเปซ [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)