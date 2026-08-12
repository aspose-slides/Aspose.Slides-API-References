---
title: MethodBase
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: "ข้อมูลพื้นฐานเกี่ยวกับเมธอด. Objects of this class ควรจะถูกจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject(). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการรับประกันที่ไม่ตรง. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr และใช้พอยน์เตอร์นี้เพื่อส่งให้ฟังก์ชันเป็นอาร์กิวเมนต์."
type: docs
weight: 118
url: /th/system.reflection/methodbase/
---
## MethodBase คลาส


ข้อมูลพื้นฐานเกี่ยวกับวิธีการ. Objects of this คลาส should only be allocated using [System::MakeObject()](../../system/makeobject/) ฟังก์ชัน. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this คลาส into [System::SmartPtr](../../system/smartptr/) พอยน์เตอร์ and use this พอยน์เตอร์ to pass it to ฟังก์ชัน as argument.

```cpp
class MethodBase : public System::Reflection::MemberInfo
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| void [AddAttribute](../memberinfo/addattribute/)(const [ObjectPtr](../memberinfo/objectptr/)\&) | เพิ่มแอตทริบิวต์ให้กับคอลเลกชัน. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจกต์โดยใช้งานเซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าทศนิยมแบบ C#-style ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN อีกด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าทศนิยมแบบ C#-style ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN อีกด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| [TypeInfo](../../system/typeinfo/) [get_DeclaringType](../memberinfo/get_declaringtype/)() const | ดึงประเภทที่ประกาศ. |
| const [String](../../system/string/)\& [get_FullName](../memberinfo/get_fullname/)() const | ดึงชื่อเต็มของสมาชิก. อาจแตกต่างในส่วนที่ทำด้วยตนเอง. |
| [MemberTypes](../membertypes/) [get_MemberType](./get_membertype/)() const override | ระบุประเภทของสมาชิก - เมธอด, คอนสตรัคเตอร์, อีเวนต์, ฯลฯ. |
| const [String](../../system/string/)\& [get_Name](../memberinfo/get_name/)() const | ดึงชื่อของสมาชิก. |
| [TypeInfo](../../system/typeinfo/) [get_ReflectedType](../memberinfo/get_reflectedtype/)() const | ดึงประเภทที่สะท้อน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจกต์. |
| static [System::SharedPtr](../../system/sharedptr/)\<[MemberInfo](../memberinfo/)\> [GetCurrentMethod](./getcurrentmethod/)(const [String](../../system/string/)\&) | เมธอดนี้อนุญาตให้ดึงชื่อเมธอดปัจจุบัน. ตัวแปลจะทดแทน ASPOSE_CURRENT_FUNCTION เป็นพารามิเตอร์โดยอัตโนมัติ. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [GetCustomAttributes](../memberinfo/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&, **bool**) const | ส่งคืนอาร์เรย์ที่ประกอบด้วยออบเจกต์ซึ่งเป็นตัวแทนของแอตทริบิวต์ที่กำหนดเองทั้งหมดที่ถูกนำไปใช้กับประเภทที่แทนโดยออบเจกต์ปัจจุบัน. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [GetCustomAttributes](../memberinfo/getcustomattributes/)(**bool**) const | ส่งคืนอาร์เรย์ที่ประกอบด้วยออบเจกต์ซึ่งเป็นตัวแทนของแอตทริบิวต์ที่กำหนดเองทั้งหมดที่ถูกนำไปใช้กับประเภทที่แทนโดยออบเจกต์ปัจจุบัน. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นสอดคล้องกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของออบเจกต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของออบเจกต์. เป็นสอดคล้องกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. สอดคล้องกับโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นสอดคล้องกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [MethodBase](./methodbase/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [MethodBase](./). |
|  [Object](../../system/object/object/)() | สร้างออบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆแล้วไม่คัดลอกอะไรเลย เพียงแค่เริ่มต้นออบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริงๆแล้วไม่คัดลอกอะไรเลย เพียงแค่เริ่มต้นออบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจกต์ประเภทค่าด้วยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็นพอยน์เตอร์แบบ weak (แทนที่แบบ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ตพอยน์เตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ตพอยน์เตอร์หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นสอดคล้องกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงออบเจกต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เป็นการปลดล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ตพอยน์เตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ตพอยน์เตอร์หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจกต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [MemberInfo](../memberinfo/)
* เนมสเปซ [System::Reflection](../)
* ไลบรารี [Aspose.Slides](../../)