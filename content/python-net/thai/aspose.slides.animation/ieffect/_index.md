---
title: IEffect class
second_title: Aspose.Slides สำหรับ Python ผ่าน .NET เอกสารอ้างอิง API
description: 
type: docs
url: /th/aspose.slides.animation/ieffect/
---
## IEffect คลาส

เป็นตัวแทนของเอฟเฟกต์การเคลื่อนไหว

ประเภท IEffect เปิดเผยสมาชิกต่อไปนี้:

## คุณสมบัติ

| Property | Description |
| :- | :- |
| [`sequence`](/slides/python-net/th/aspose.slides.animation/ieffect/sequence/) | คืนค่าลำดับของเอฟเฟกต์.<br/>            Read-only [`ISequence`](/slides/python-net/th/aspose.slides.animation/isequence). |
| [`text_animation`](/slides/python-net/th/aspose.slides.animation/ieffect/text_animation/) | คืนค่าการเคลื่อนไหวของข้อความ.<br/>            Read-only [`ITextAnimation`](/slides/python-net/th/aspose.slides.animation/itextanimation). |
| [`preset_class_type`](/slides/python-net/th/aspose.slides.animation/ieffect/preset_class_type/) | กำหนดคลาสของเอฟเฟกต์.<br/>            Read/write [`EffectPresetClassType`](/slides/python-net/th/aspose.slides.animation/effectpresetclasstype). |
| [`type`](/slides/python-net/th/aspose.slides.animation/ieffect/type/) | กำหนดประเภทของเอฟเฟกต์.<br/>            Read/write [`EffectType`](/slides/python-net/th/aspose.slides.animation/effecttype). |
| [`subtype`](/slides/python-net/th/aspose.slides.animation/ieffect/subtype/) | กำหนดชนิดย่อยของเอฟเฟกต์.<br/>            Read/write [`EffectSubtype`](/slides/python-net/th/aspose.slides.animation/effectsubtype). |
| [`behaviors`](/slides/python-net/th/aspose.slides.animation/ieffect/behaviors/) | คืนค่าคอลเลกชันของพฤติกรรมสำหรับเอฟเฟกต์.<br/>            Read/write [`IBehaviorCollection`](/slides/python-net/th/aspose.slides.animation/ibehaviorcollection). |
| [`timing`](/slides/python-net/th/aspose.slides.animation/ieffect/timing/) | กำหนดค่าเวลาให้กับเอฟเฟกต์.<br/>            Read/write [`ITiming`](/slides/python-net/th/aspose.slides.animation/itiming). |
| [`target_shape`](/slides/python-net/th/aspose.slides.animation/ieffect/target_shape/) | คืนรูปร่างเป้าหมายสำหรับเอฟเฟกต์.<br/>            Read-only [`IShape`](/slides/python-net/th/aspose.slides/ishape). |
| [`sound`](/slides/python-net/th/aspose.slides.animation/ieffect/sound/) | กำหนดเสียงฝังในเอฟเฟกต์.<br/>            Read/write [`IAudio`](/slides/python-net/th/aspose.slides/iaudio). |
| [`stop_previous_sound`](/slides/python-net/th/aspose.slides.animation/ieffect/stop_previous_sound/) | คุณลักษณะนี้ระบุว่าเอฟเฟกต์การเคลื่อนไหวจะหยุดเสียงก่อนหน้าหรือไม่.<br/>            Read/write **bool**. |
| [`after_animation_type`](/slides/python-net/th/aspose.slides.animation/ieffect/after_animation_type/) | กำหนดประเภทของการเคลื่อนไหวหลังจากเอฟเฟกต์.<br/>            Read/write [`IEffect.after_animation_type`](/slides/python-net/th/aspose.slides.animation/ieffect/after_animation_type). |
| [`after_animation_color`](/slides/python-net/th/aspose.slides.animation/ieffect/after_animation_color/) | กำหนดสีของการเคลื่อนไหวหลังจากเอฟเฟกต์.<br/>            Read/write [`IColorFormat`](/slides/python-net/th/aspose.slides/icolorformat). |
| [`animate_text_type`](/slides/python-net/th/aspose.slides.animation/ieffect/animate_text_type/) | กำหนดประเภทการเคลื่อนไหวของข้อความสำหรับเอฟเฟกต์.<br/>            ข้อความของ shape สามารถเคลื่อนไหวได้ตามตัวอักษร, ตามคำ หรือทั้งหมดพร้อมกัน.<br/>            Read/write [`IEffect.animate_text_type`](/slides/python-net/th/aspose.slides.animation/ieffect/animate_text_type). |
| [`delay_between_text_parts`](/slides/python-net/th/aspose.slides.animation/ieffect/delay_between_text_parts/) | กำหนดความล่าช้าระหว่างส่วนของข้อความที่เคลื่อนไหว (คำหรืออักขระ).<br/>            ค่าบวกระบุเปอร์เซ็นต์ของระยะเวลาเอฟเฟกต์.<br/>            ค่าลบระบุความล่าช้าเป็นวินาที.<br/>            Read/write **float**. |

### ดูเพิ่มเติม
* โมดูล [`aspose.slides.animation`](/slides/python-net/th/aspose.slides.animation)
* ห้องสมุด [`Aspose.Slides`](/slides/python-net)