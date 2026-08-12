---
title: get_AnimateTextType()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดประเภทการเคลื่อนไหวของข้อความสำหรับเอฟเฟกต์ ข้อความในรูปทรงสามารถเคลื่อนไหวได้ตามตัวอักษร ตามคำ หรือทั้งหมดในครั้งเดียว อ่าน AnimateTextType.
type: docs
weight: 274
url: /th/aspose.slides.animation/ieffect/get_animatetexttype/
---
## IEffect::get_AnimateTextType() เมธอด

กำหนดประเภทการเคลื่อนไหวของข้อความสำหรับเอฟเฟกต์ ข้อความในรูปทรงสามารถเคลื่อนไหวได้ตามตัวอักษร ตามคำ หรือทั้งหมดในครั้งเดียว อ่าน [AnimateTextType](../../animatetexttype/).

```cpp
virtual Aspose::Slides::Animation::AnimateTextType Aspose::Slides::Animation::IEffect::get_AnimateTextType()=0
```

## หมายเหตุ

```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// รับเอฟเฟกต์แรกของสไลด์แรก.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// เปลี่ยนประเภทการเคลื่อนไหวของข้อความของเอฟเฟกต์เป็น "by letter"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByLetter);
```

## ดูเพิ่มเติม

* Enum [AnimateTextType](../../animatetexttype/)
* Class [IEffect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)