---
title: Timing
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงการกำหนดเวลาแอนิเมชัน.
type: docs
weight: 625
url: /th/aspose.slides.animation/timing/
---
## คลาส Timing

Represents animation timing.

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# โดยที่ NaN สองค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# โดยที่ NaN สองค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| **float** [get_Accelerate](./get_accelerate/)() override | อธิบายร้อยละของผลกระทบการเร่งพฤติกรรมตามระยะเวลา อ่าน **float**. |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | อธิบายว่าจะเล่นแอนิเมชันโดยอัตโนมัติแบบย้อนกลับหลังจากเล่นในทิศทางต่อหน้า หรือไม่ อ่าน **bool**. |
| **float** [get_Decelerate](./get_decelerate/)() override | อธิบายร้อยละของผลกระทบการชะลอพฤติกรรมตามระยะเวลา อ่าน **float**. |
| **float** [get_Duration](./get_duration/)() override | อธิบายระยะเวลาของผลกระทบแอนิเมชัน อ่าน **float**. |
| **float** [get_RepeatCount](./get_repeatcount/)() override | อธิบายจำนวนครั้งที่ผลกระทบควรทำซ้ำ อ่าน **float**. |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | อธิบายจำนวนครั้งที่ผลกระทบควรทำซ้ำ อ่าน **float**. |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | แอตทริบิวต์นี้ระบุว่าผลกระทบจะทำซ้ำจนจบสไลด์หรือไม่ อ่าน **bool**. |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | แอตทริบิวต์นี้ระบุว่าผลกระทบจะทำซ้ำจนการคลิกครั้งถัดไปหรือไม่ อ่าน **bool**. |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | ระบุว่าผลกระทบควรเริ่มใหม่หลังจากเสร็จหรือไม่ อ่าน [EffectRestartType](../effectrestarttype/). |
| **bool** [get_Rewind](./get_rewind/)() override | แอตทริบิวต์นี้ระบุว่าผลกระทบจะย้อนกลับเมื่อเล่นเสร็จหรือไม่ อ่าน **bool**. |
| **float** [get_Speed](./get_speed/)() override | ระบุร้อยละที่ต้องการเร่ง (หรือชะลอ) เวลาอ่าน **float**. |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | อธิบายเวลาหน่วงหลังการกระตุ้น อ่าน **float**. |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | อธิบายประเภทการกระตุ้น อ่าน [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาชนิดกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์ตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์ตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงของอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การแปรรูปของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การแปรรูปของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่กำหนด. |
| void [set_Accelerate](./set_accelerate/)(**float**) override | อธิบายร้อยละของผลกระทบการเร่งพฤติกรรมตามระยะเวลา เขียน **float**. |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | อธิบายว่าจะเล่นแอนิเมชันโดยอัตโนมัติแบบย้อนกลับหลังจากเล่นในทิศทางต่อหน้า หรือไม่ เขียน **bool**. |
| void [set_Decelerate](./set_decelerate/)(**float**) override | อธิบายร้อยละของผลกระทบการชะลอพฤติกรรมตามระยะเวลา เขียน **float**. |
| void [set_Duration](./set_duration/)(**float**) override | อธิบายระยะเวลาของผลกระทบแอนิเมชัน เขียน **float**. |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | อธิบายจำนวนครั้งที่ผลกระทบควรทำซ้ำ เขียน **float**. |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | อธิบายจำนวนครั้งที่ผลกระทบควรทำซ้ำ เขียน **float**. |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | แอตทริบิวต์นี้ระบุว่าผลกระทบจะทำซ้ำจนจบสไลด์หรือไม่ เขียน **bool**. |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | แอตทริบิวต์นี้ระบุว่าผลกระทบจะทำซ้ำจนการคลิกครั้งถัดไปหรือไม่ เขียน **bool**. |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | ระบุว่าผลกระทบควรเริ่มใหม่หลังจากเสร็จหรือไม่ เขียน [EffectRestartType](../effectrestarttype/). |
| void [set_Rewind](./set_rewind/)(**bool**) override | แอตทริบิวต์นี้ระบุว่าผลกระทบจะย้อนกลับเมื่อเล่นเสร็จหรือไม่ เขียน **bool**. |
| void [set_Speed](./set_speed/)(**float**) override | ระบุร้อยละที่ต้องการเร่ง (หรือชะลอ) เวลา เขียน **float**. |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | อธิบายเวลาหน่วงหลังการกระตุ้น เขียน **float**. |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | อธิบายประเภทการกระตุ้น เขียน [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กูเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับ weak reference. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับ weak reference. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [ITiming](../itiming/)
* คลาส [IDOMObject](../../aspose.slides/idomobject/)
* เนมสเปซ [Aspose::Slides::Animation](../)
* ไลบรารี [Aspose.Slides](../../)