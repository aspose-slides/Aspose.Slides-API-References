---
title: XmlQualifiedName
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงชื่อที่มีการกำหนดคุณลักษณะของ XML.
type: docs
weight: 417
url: /th/system.xml/xmlqualifiedname/
---
## XmlQualifiedName คลาส


แสดงถึงชื่อที่มีการกำหนดคุณลักษณะของ XML.

```cpp
class XmlQualifiedName : public System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | กำหนดว่าวัตถุ [XmlQualifiedName](./) ที่ระบุเท่ากับวัตถุปัจจุบันของ [XmlQualifiedName](./) หรือไม่. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ซึ่งสองค่า NaN จะถือเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด-ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ซึ่งสองค่า NaN จะถือเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด-ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| **bool** [get_IsEmpty](./get_isempty/)() const | คืนค่าแสดงว่าตัวแปร [XmlQualifiedName](./) ว่างหรือไม่. |
| [String](../../system/string/) [get_Name](./get_name/)() const | คืนค่าการแทนสตริงของชื่อที่กำหนดของ [XmlQualifiedName](./). |
| [String](../../system/string/) [get_Namespace](./get_namespace/)() const | คืนค่าการแทนสตริงของเนมสเปซของ [XmlQualifiedName](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | คืนค่ารหัสแฮชสำหรับ [XmlQualifiedName](./). |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ นิรนามของการเรียก [System.Object.GetType()](../../system/object/gettype/) ใน C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ นิรนามของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | นิรนามของเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# เปิดใช้งานการคล cloning ประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรเลย จริง ๆ แล้วเพียงเริ่มต้นวัตถุใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรเลย จริง ๆ แล้วเพียงเริ่มต้นวัตถุใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุตามการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงของวัตถุประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared) ทำให้สามารถสลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าจำนวนการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| static [String](../../system/string/) [ToString](./tostring/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | คืนค่าสตริงของ [XmlQualifiedName](./). |
| [String](../../system/string/) [ToString](./tostring/)() const override | คืนค่าสตริงของ [XmlQualifiedName](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
|  [XmlQualifiedName](./xmlqualifiedname/)() | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlQualifiedName](./). |
|  [XmlQualifiedName](./xmlqualifiedname/)(const [String](../../system/string/)\&) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlQualifiedName](./) ด้วยชื่อที่ระบุ. |
|  [XmlQualifiedName](./xmlqualifiedname/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [XmlQualifiedName](./) ด้วยชื่อและเนมสเปซที่ระบุ. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [Empty](./empty/) | ให้ [XmlQualifiedName](./) ที่ว่างเปล่า. |

## การกำหนดชนิด

| Typedef | คำอธิบาย |
| --- | --- |
| [Ptr](./ptr/) | นามแฝงสำหรับ shared pointer ไปยังอินสแตนซ์ของคลาสนี้. |

## หมายเหตุ



ออบเจกต์ของคลาสนี้ควรจัดสรรด้วยฟังก์ชัน [System::MakeObject()](../../system/makeobject/) เท่านั้น ห้ามสร้างอินสแตนซ์ของประเภทนี้บนสแตคหรือโดยใช้โอเปอเรเตอร์ new เพราะจะทำให้เกิดข้อผิดพลาดในเวลารันไทม์และ/หรือการตรวจสอบความถูกต้อง ควรห่อครอบคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยเตอร์นี้ส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชันเสมอ. 

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Xml](../)
* ไลบรารี [Aspose.Slides](../../)