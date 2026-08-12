---
title: IFieldType
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงประเภทของฟิลด์ ค่าตัวนี้กำหนดว่าจะตั้งข้อความใดให้กับส่วนของฟิลด์เมื่อทำการอัปเดต
type: docs
weight: 2094
url: /th/aspose.slides/ifieldtype/
---
## IFieldType คลาส

Represents a type of field. This value determines which text will be set to the field portion when it will be updated.

```cpp
class IFieldType : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขจุดลอยแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขจุดลอยแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น |
| virtual [System::String](../../system/string/) [get_InternalString](./get_internalstring/)() | คืนค่าชื่อภายในของอ็อบเจ็กต์ FieldTypeEx นี้ อ่าน [System::String](../../system/string/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นฟังก์ชันเทียบเท่าของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นฟังก์ชันเทียบเท่ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เทียบเท่ากับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นฟังก์ชันเทียบเท่ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และทำให้สามารถคัดลอกสร้างซับคลาสได้ |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอร์เรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และทำให้สามารถคัดลอกสร้างซับคลาสได้ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดค่าเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดค่าเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบแชร์ลงตามค่าที่ระบุ |
| virtual void [set_InternalString](./set_internalstring/)([System::String](../../system/string/)) | คืนค่าชื่อภายในของอ็อบเจ็กต์ FieldTypeEx นี้ เขียน [System::String](../../system/string/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | กำหนดอาร์กิวเมนต์เทมเพลตลำดับที่ n ให้เป็น weak pointer (แทนที่ shared) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้ |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแบบแชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบแชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงแบบแชร์และคืนค่า ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นฟังก์ชันเทียบเท่ของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมส페ซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)