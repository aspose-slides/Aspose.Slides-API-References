---
title: ConstructorInfo
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: ให้การเข้าถึงเมตาดาต้าของคอนสตรัคเตอร์.
type: docs
weight: 53
url: /th/system.reflection/constructorinfo/
---
## ConstructorInfo คลาส

ให้การเข้าถึงเมตาดาต้าของคอนสตรัคเตอร์.

```cpp
class ConstructorInfo : public System::Reflection::MethodBase
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [AddAttribute](../memberinfo/addattribute/)(const [ObjectPtr](../memberinfo/objectptr/)\&) | เพิ่มแอตทริบิวต์ลงในคอลเลกชัน. |
|  [ConstructorInfo](./constructorinfo/)(const [String](../../system/string/)\&, std::function\<[System::Object::ptr](../../system/object/ptr/)()>) | สร้างอินสแตนซ์ใหม่ของคลาส [ConstructorInfo](./) สำหรับคอนสตรัคเตอร์ที่ไม่มีพารามิเตอร์. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น. |
| [TypeInfo](../../system/typeinfo/) [get_DeclaringType](./get_declaringtype/)() | รับคลาสที่ประกาศสมาชิกนี้. NOT IMPLEMENTED. |
| [TypeInfo](../../system/typeinfo/) [get_DeclaringType](../memberinfo/get_declaringtype/)() const | รับประเภทที่ประกาศ. |
| const [String](../../system/string/)\& [get_FullName](../memberinfo/get_fullname/)() const | รับชื่อเต็มของสมาชิก. อาจแตกต่างกันในส่วนที่ทำมือ. |
| [MemberTypes](../membertypes/) [get_MemberType](./get_membertype/)() const override | รับค่า MemberTypes ที่บ่งบอกว่าสมาชิกนี้เป็นคอนสตรัคเตอร์. |
| const [String](../../system/string/)\& [get_Name](../memberinfo/get_name/)() const | รับชื่อของสมาชิก. |
| [TypeInfo](../../system/typeinfo/) [get_ReflectedType](../memberinfo/get_reflectedtype/)() const | รับประเภทที่สะท้อนของ type. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| static [System::SharedPtr](../../system/sharedptr/)\<[MemberInfo](../memberinfo/)\> [GetCurrentMethod](../methodbase/getcurrentmethod/)(const [String](../../system/string/)\&) | เมธอดนี้อนุญาตให้รับชื่อเมธอดปัจจุบัน. ตัวแปลจะใส่ ASPOSE_CURRENT_FUNCTION เป็นพารามิเตอร์โดยอัตโนมัติ. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [GetCustomAttributes](../memberinfo/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&, **bool**) const | คืนค่าอาร์เรย์ที่ประกอบด้วยอ็อบเจ็กต์ที่แสดงถึงแอตทริบิวต์แบบกำหนดเองทั้งหมดที่ถูกนำไปใช้กับประเภทที่แทนโดยอ็อบเจ็กต์ปัจจุบัน. |
| [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\> [GetCustomAttributes](../memberinfo/getcustomattributes/)(**bool**) const | คืนค่าอาร์เรย์ที่ประกอบด้วยอ็อบเจ็กต์ที่แสดงถึงแอตทริบิวต์แบบกำหนดเองทั้งหมดที่ถูกนำไปใช้กับประเภทที่แทนโดยอ็อบเจ็กต์ปัจจุบัน. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [Invoke](./invoke/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\>\&) | เรียกเมธอดหรือคอนสตรัคเตอร์ที่แทนโดยอินสแตนซ์ปัจจุบัน โดยใช้พารามิเตอร์ที่ระบุ. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาประเภทแบบกำหนดเอง. |
|  [MethodBase](../methodbase/methodbase/)() | สร้างอินสแตนซ์ใหม่ของคลาส [MethodBase](../methodbase/). |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกของคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์มอบหมายค่า. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกของคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงของอ็อบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่จะเป็น shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [MethodBase](../methodbase/)
* เนมสเปซ [System::Reflection](../)
* ไลบรารี [Aspose.Slides](../../)