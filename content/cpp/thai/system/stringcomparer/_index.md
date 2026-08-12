---
title: StringComparer
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: "เปรียบเทียบสตริงโดยใช้โหมดการเปรียบเทียบที่แตกต่างกัน. อ็อบเจกต์ของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject() . ไม่ควรสร้างอินสแตนซ์ของประเภทนี้บนสแต็กหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยพอยเตอร์ System::SmartPtr และใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 1288
url: /th/system/stringcomparer/
---
## StringComparer คลาส

เปรียบเทียบสตริงโดยใช้โหมดการเปรียบเทียบที่แตกต่างกัน. อ็อบเจกต์ของคลาสนี้ควรจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../makeobject/). ห้ามสร้างอินสแตนซ์ของชนิดนี้บนสแต็คหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ด้วยพอยเตอร์ [System::SmartPtr](../smartptr/) เสมอและใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class StringComparer : public virtual System::Object,
                       public System::Collections::Generic::IComparer<String>,
                       public System::Collections::Generic::IEqualityComparer<String>
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| int [Compare](./compare/)([args_type](./args_type/), [args_type](./args_type/)) const override | เปรียบเทียบสตริงสองค่าโดยใช้การตั้งค่าปัจจุบัน |
| static [StringComparerPtr](../stringcomparerptr/) [Create](./create/)(const [System::SharedPtr](../sharedptr/)\<[System::Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **bool**) | สร้างออบเจกต์เปรียบเทียบที่เจาะจงตามวัฒนธรรม |
| **bool** [Equals](./equals/)([String](../string/), [String](../string/)) const override | ตรวจว่าสตริงสองค่าเท่ากันหรือไม่โดยใช้การตั้งค่าปัจจุบัน |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../object/equals/) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C# |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับใช้ภายในเท่านั้น |
| static [StringComparerPtr](../stringcomparerptr/) [get_CurrentCulture](./get_currentculture/)() | อ็อบเจกต์ singleton ของตัวเปรียบเทียบวัฒนธรรมปัจจุบัน |
| static [StringComparerPtr](../stringcomparerptr/) [get_CurrentCultureIgnoreCase](./get_currentcultureignorecase/)() | อ็อบเจกต์ singleton ของตัวเปรียบเทียบวัฒนธรรมปัจจุบันที่ไม่แยกแยะตัวพิมพ์ใหญ่/เล็ก |
| static [StringComparerPtr](../stringcomparerptr/) [get_InvariantCulture](./get_invariantculture/)() | อ็อบเจกต์ singleton ของตัวเปรียบเทียบวัฒนธรรมที่คงที่ |
| static [StringComparerPtr](../stringcomparerptr/) [get_InvariantCultureIgnoreCase](./get_invariantcultureignorecase/)() | อ็อบเจกต์ singleton ของตัวเปรียบเทียบวัฒนธรรมที่คงที่ที่ไม่แยกแยะตัวพิมพ์ใหญ่/เล็ก |
| static [StringComparerPtr](../stringcomparerptr/) [get_Ordinal](./get_ordinal/)() | อ็อบเจกต์ singleton ของตัวเปรียบเทียบแบบ ordinal |
| static [StringComparerPtr](../stringcomparerptr/) [get_OrdinalIgnoreCase](./get_ordinalignorecase/)() | อ็อบเจกต์ singleton ของตัวเปรียบเทียบแบบ ordinal ที่ไม่แยกแยะตัวพิมพ์ใหญ่/เล็ก |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| int [GetHashCode](./gethashcode/)([String](../string/)) const override | รับค่าแฮชโค้ดของสตริง |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../object/gethashcode/). เปิดใช้งานการแฮชของวัตถุที่กำหนดเอง |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | รับประเภทที่แท้จริงของอ็อบเจกต์. คล้ายกับการเรียก C# [System.Object.GetType()](../object/gettype/) |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับอปอเรเตอร์ 'is' ของ C# |
| void [Lock](../object/lock/)() | ทำหน้าที่ล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). เปิดใช้งานการเลียนแบบประเภทที่กำหนดเอง |
|  [Object](../object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | โอเปอเรเตอร์มอบหมายค่า. จริงๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การกำหนดเฉพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การกำหนดเฉพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงหลายค่า |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบแชร์ตามค่าที่ระบุ |
|  [RTTI_INFO_TEMPLATE_CLASS](../../system.collections.generic/iequalitycomparer/rtti_info_template_class/)([System::Collections::Generic::IEqualityComparer](../../system.collections.generic/iequalitycomparer/)\<T\>, System::BaseTypesInfo\<[System::Object](../object/)\>) | ข้อมูล RTTI |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็นพอยเตอร์แบบเวก (แทนที่จะแชร์). อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมดเวก |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแบบแชร์ |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยเตอร์หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงแบบแชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยเตอร์หรือ ThisProtector แทน |
| virtual [String](../string/) [ToString](../object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ทำหน้าที่สร้างโครงสร้าง typeof([System.Object](../object/)) ของ C# |
| void [Unlock](../object/unlock/)() | ทำหน้าที่ปลดล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบเวก. ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยเตอร์หรือ ThisProtector แทน |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบเวก. ไม่ควรเรียกโดยตรง; ใช้สมาร์ทพอยเตอร์หรือ ThisProtector แทน |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ประเภทกำหนด

| ชนิดกำหนด | คำอธิบาย |
| --- | --- |
| [args_type](./args_type/) | ประเภทของอาร์กิวเมนต์ |

## ดูเพิ่มเติม

* คลาส [Object](../object/)
* คลาส [IComparer](../../system.collections.generic/icomparer/)
* คลาส [IEqualityComparer](../../system.collections.generic/iequalitycomparer/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)