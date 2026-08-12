---
title: ToBase64Transform
second_title: Aspose.Slides สำหรับการอ้างอิง API C++
description: "แปลงอินสแตนซ์ของคลาส CryptoStream ไปเป็น base 64. อ็อบเจกต์ของคลาสนี้ควรได้รับการจัดสรรผ่านฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการขัดแย้งของการตรวจสอบ. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งผ่านเป็นอากูเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 664
url: /th/system.security.cryptography/tobase64transform/
---
## คลาส ToBase64Transform

แปลงอินสแตนซ์ของคลาส [CryptoStream](../cryptostream/) ไปเป็น base 64. อ็อบเจกต์ของคลาสนี้ควรได้รับการจัดสรรผ่านฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new, เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือการขัดแย้งของการตรวจสอบ. ควรห่อคลาสนี้ด้วยตัวชี้ [System::SmartPtr](../../system/smartptr/) และใช้ตัวชี้นี้เพื่อส่งผ่านเป็นอากุเมนต์ให้กับฟังก์ชัน.

```cpp
class ToBase64Transform : public System::Security::Cryptography::ICryptoTransform
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Clear](./clear/)() | ปล่อยทรัพยากรทั้งหมด. |
| void [Dispose](./dispose/)() | ปล่อยทรัพยากรของระบบปฏิบัติการที่ออบเจกต์ปัจจุบันได้จัดสรร. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ NaN สองค่าเป็นค่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ NaN สองค่าเป็นค่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| virtual **bool** [get_CanReuseTransform](./get_canreusetransform/)() | รับค่าที่บ่งชี้ว่าการแปลงปัจจุบันสามารถใช้ซ้ำได้หรือไม่. |
| **bool** [get_CanTransformMultipleBlocks](./get_cantransformmultipleblocks/)() | รับค่าที่บ่งชี้ว่าบล็อกหลายรายการสามารถแปลงได้หรือไม่. |
| virtual **int32_t** [get_InputBlockSize](./get_inputblocksize/)() | ขนาดของบล็อกอินพุต. |
| virtual **int32_t** [get_OutputBlockSize](./get_outputblocksize/)() | ขนาดของบล็อกเอาต์พุต. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของออบเจกต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจกต์. เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอนาล็อกของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างออบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลออะไรเลย เพียงแค่เริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลออะไรเลย เพียงแค่เริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงโดยค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่จะแชร์). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงออบเจกต์ที่กำหนดเองเป็นสตริง. |
| **int32_t** [TransformBlock](./transformblock/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**, [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**) | ประมวลผลบล็อกข้อมูลและคัดลอกข้อมูลไปยังอาเรย์เอาต์พุต. |
| virtual int [TransformBlock](../icryptotransform/transformblock/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | ประมวลผลบล็อกข้อมูลและคัดลอกข้อมูลไปยังอาเรย์เอาต์พุต. |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [TransformFinalBlock](./transformfinalblock/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, **int32_t**, **int32_t**) | ประมวลผลบล็อกข้อมูลสุดท้ายและคำนวณค่าเอาต์พุต. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [TransformFinalBlock](../icryptotransform/transformfinalblock/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | ประมวลผลบล็อกข้อมูลสุดท้ายและคำนวณค่าเอาต์พุต. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เป็นการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
| virtual  [~ToBase64Transform](./~tobase64transform/)() | ตัวทำลาย. |

## ดูเพิ่มเติม

* คลาส [ICryptoTransform](../icryptotransform/)
* เนมสเปซ [System::Security::Cryptography](../)
* ไลบรารี [Aspose.Slides](../../)