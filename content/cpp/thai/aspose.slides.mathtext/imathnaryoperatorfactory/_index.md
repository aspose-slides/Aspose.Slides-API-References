---
title: IMathNaryOperatorFactory
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: อนุญาตให้สร้าง IMathNaryOperator
type: docs
weight: 430
url: /th/aspose.slides.mathtext/imathnaryoperatorfactory/
---
## IMathNaryOperatorFactory คลาส


Allows to create [IMathNaryOperator](../imathnaryoperator/)

```cpp
class IMathNaryOperatorFactory : public virtual System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [CreateMathNaryOperator](./createmathnaryoperator/)(char16_t, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้าง [IMathNaryOperator](../imathnaryoperator/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [CreateMathNaryOperator](./createmathnaryoperator/)(char16_t, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้าง [IMathNaryOperator](../imathnaryoperator/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [CreateMathNaryOperator](./createmathnaryoperator/)(char16_t, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](../imathelement/)\>) | สร้าง [IMathNaryOperator](../imathnaryoperator/) |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้รูปแบบการทำงานของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ซึ่ง NaN สองค่าถือเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าที่ใดๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ซึ่ง NaN สองค่าถือเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าที่ใดๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถทำแฮชอ็อบเจ็กต์แบบกำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรักเตอร์ของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไร จริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรักเตอร์ของซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายค่า. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่จะเป็น shared) ซึ่งอนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์ไปยังโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; แทนใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; แทนใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; แทนใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak ควรไม่เรียกโดยตรง; แทนใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## หมายเหตุ


For COM comparibility 
## ดูเพิ่ม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides::MathText](../)
* ไลบรารี [Aspose.Slides](../../)