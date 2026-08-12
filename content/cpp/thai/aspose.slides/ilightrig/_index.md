---
title: ILightRig
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แทน LightRig.
type: docs
weight: 2705
url: /th/aspose.slides/ilightrig/
---
## ILightRig คลาส

เป็นตัวแทนของ [LightRig](../lightrig/).

```cpp
class ILightRig : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบ floating point แบบ C#-style ที่ในนั้น NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบ floating point แบบ C#-style ที่ในนั้น NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual [LightingDirection](../lightingdirection/) [get_Direction](./get_direction/)() | ทิศทางแสง. อ่าน [LightingDirection](../lightingdirection/). |
| virtual [LightRigPresetType](../lightrigpresettype/) [get_LightType](./get_lighttype/)() | แสดงถึงแสง preset ที่สามารถนำไปใช้กับรูปร่างได้. light rig แสดงถึงกลุ่มของแสงที่จัดแนวในลักษณะเฉพาะสัมพันธ์กับฉาก 3D. อ่าน [LightRigPresetType](../lightrigpresettype/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนุกรมของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจ็กต์แบบกำหนดเอง. |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [GetRotation](./getrotation/)() | การหมุนถูกกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนเป็นพิกัดละติจูดและลองจิจูด. first element in return array - latitude, second - longitude, third - revolution. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นอนุกรมของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอนุกรมของโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentinel. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนุกรมของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาของชนิดกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, stdscrnullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงด้วยค่าที่ระบุ. |
| virtual void [set_Direction](./set_direction/)([LightingDirection](../lightingdirection/)) | ทิศทางแสง. เขียน [LightingDirection](../lightingdirection/). |
| virtual void [set_LightType](./set_lighttype/)([LightRigPresetType](../lightrigpresettype/)) | แสดงถึงแสง preset ที่สามารถนำไปใช้กับรูปร่างได้. light rig แสดงถึงกลุ่มของแสงที่จัดแนวในลักษณะเฉพาะสัมพันธ์กับฉาก 3D. เขียน [LightRigPresetType](../lightrigpresettype/). |
| virtual void [SetRotation](./setrotation/)(**float**, **float**, **float**) | การหมุนถูกกำหนดโดยการใช้พิกัดละติจูด, พิกัดลองจิจูด, และการหมุนรอบแกนเป็นพิกัดละติจูดและลองจิจูด. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า argument template ที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่นั้นให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; แทนที่นั้นให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนุกรมของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตาม construct typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentinel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่นั้นให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่นั้นให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)