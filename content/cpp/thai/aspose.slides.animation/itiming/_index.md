---
title: ITiming
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงการตั้งเวลาแอนิเมชัน.
type: docs
weight: 443
url: /th/aspose.slides.animation/itiming/
---
## คลาส ITiming

แสดงถึงการตั้งเวลาแอนิเมชัน.

```cpp
class ITiming : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ไวยากรณ์ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตัวสไตล์ C# ที่ NaN สองค่าถูกมองว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaNด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตัวสไตล์ C# ที่ NaN สองค่าถูกมองว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaNด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| virtual **float** [get_Accelerate](./get_accelerate/)() | อธิบายเปอร์เซ็นต์ของผลการกระทำเร่งความเร็วของระยะเวลา. อ่าน **float**. |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | อธิบายว่าจะแค่เล่นแอนิเมชันแบบย้อนกลับโดยอัตโนมัติหลังจากเล่นในทิศทางไปข้างหน้า หรือไม่. อ่าน **bool**. |
| virtual **float** [get_Decelerate](./get_decelerate/)() | อธิบายเปอร์เซ็นต์ของผลการกระทำลดความเร็วของระยะเวลา. อ่าน **float**. |
| virtual **float** [get_Duration](./get_duration/)() | อธิบายระยะเวลาของผลแอนิเมชัน. อ่าน **float**. |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | อธิบายจำนวนครั้งที่ผลควรทำซ้ำ. อ่าน **float**. |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | อธิบายจำนวนครั้งที่ผลควรทำซ้ำ. อ่าน **float**. |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | แอตทริบิวต์นี้ระบุว่าผลจะทำซ้ำจนจบสไลด์หรือไม่. อ่าน **bool**. |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | แอตทริบิวต์นี้ระบุว่าผลจะทำซ้ำจนการคลิกครั้งถัดไปหรือไม่. อ่าน **bool**. |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | ระบุว่าผลควรเริ่มต้นใหม่หลังจากเสร็จสิ้นหรือไม่. อ่าน [EffectRestartType](../effectrestarttype/). |
| virtual **bool** [get_Rewind](./get_rewind/)() | แอตทริบิวต์นี้ระบุว่าผลจะย้อนกลับเมื่อเล่นเสร็จหรือไม่. อ่าน **bool**. |
| virtual **float** [get_Speed](./get_speed/)() | ระบุเปอร์เซ็นต์ที่ต้องการเร่ง (หรือชะลอ) เวลา. อ่าน **float**. |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | อธิบายเวลาหน่วงหลังจากกระตุ้น. อ่าน **float**. |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | อธิบายประเภทของการกระตุ้น. อ่าน [EffectTriggerType](../effecttriggertype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเท่ากับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์แบบกำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เทียบเท่าการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เทียบเท่าตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามข้อความ lock() ของ C# สำหรับการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเท่ากับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถคัดลอกประเภทแบบกำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาชนิดย่อยได้. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาชนิดย่อยได้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบค่าอ็อบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่ใช้ร่วมกันโดยค่าที่ระบุ. |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | อธิบายเปอร์เซ็นต์ของผลการกระทำเร่งความเร็วของระยะเวลา. เขียน **float**. |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | อธิบายว่าจะแค่เล่นแอนิเมชันแบบย้อนกลับโดยอัตโนมัติหลังจากเล่นในทิศทางไปข้างหน้า หรือไม่. เขียน **bool**. |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | อธิบายเปอร์เซ็นต์ของผลการกระทำลดความเร็วของระยะเวลา. เขียน **float**. |
| virtual void [set_Duration](./set_duration/)(**float**) | อธิบายระยะเวลาของผลแอนิเมชัน. เขียน **float**. |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | อธิบายจำนวนครั้งที่ผลควรทำซ้ำ. เขียน **float**. |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | อธิบายจำนวนครั้งที่ผลควรทำซ้ำ. เขียน **float**. |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | แอตทริบิวต์นี้ระบุว่าผลจะทำซ้ำจนจบสไลด์หรือไม่. เขียน **bool**. |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | แอตทริบิวต์นี้ระบุว่าผลจะทำซ้ำจนการคลิกครั้งถัดไปหรือไม่. เขียน **bool**. |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | ระบุว่าผลควรเริ่มต้นใหม่หลังจากเสร็จสิ้นหรือไม่. เขียน [EffectRestartType](../effectrestarttype/). |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | แอตทริบิวต์นี้ระบุว่าผลจะย้อนกลับเมื่อเล่นเสร็จหรือไม่. เขียน **bool**. |
| virtual void [set_Speed](./set_speed/)(**float**) | ระบุเปอร์เซ็นต์ที่ต้องการเร่ง (หรือชะลอ) เวลา. เขียน **float**. |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | อธิบายเวลาหน่วงหลังจากกระตุ้น. เขียน **float**. |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | อธิบายประเภทของการกระตุ้น. เขียน [EffectTriggerType](../effecttriggertype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้เปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเท่ากับเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามคอนสตรัคต์ C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่งปลดล็อก lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides::Animation](../)
* ไลบรารี [Aspose.Slides](../../)