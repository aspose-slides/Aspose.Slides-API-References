---
title: FieldType
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แสดงถึงประเภทของฟิลด์ ค่าตัวนี้กำหนดว่าข้อความใดจะถูกตั้งค่าให้กับส่วนของฟิลด์เมื่อมีการอัปเดต
type: docs
weight: 872
url: /th/aspose.slides/fieldtype/
---
## FieldType คลาส

แสดงถึงประเภทของฟิลด์ ค่าตัวนี้กำหนดว่าข้อความใดจะถูกตั้งค่าให้กับส่วนของฟิลด์เมื่อมีการอัปเดต

```cpp
class FieldType : public Aspose::Slides::IFieldType
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | ตรวจสอบว่าฟิลด์นี้เท่ากับฟิลด์อื่นหรือไม่ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้การทำงานของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบแบบ floating point ของ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบแบบ floating point ของ C# ที่ถือว่า NaN สองค่าเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อใช้ภายในเท่านั้น |
|  [FieldType](./fieldtype/)([System::String](../../system/string/)) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [FieldType](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime](./get_datetime/)() | วันที่และเวลาปัจจุบันในรูปแบบวัน-เวลาเริ่มต้นสำหรับแอปพลิเคชันการเรนเดอร์ ไม่สามารถแก้ไขได้ [FieldType](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime1](./get_datetime1/)() | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดไว้เป็นอันดับแรก (MM/DD/YYYY สำหรับภาษาอังกฤษ) ไม่สามารถแก้ไขได้ [FieldType](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime10](./get_datetime10/)() | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดไว้เป็นอันดับสิบ (hh:mm สำหรับภาษาอังกฤษ) ไม่สามารถแก้ไขได้ [FieldType](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime11](./get_datetime11/)() | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดไว้เป็นอันดับสิบเอ็ด (hh:mm:ss สำหรับภาษาอังกฤษ) ไม่สามารถแก้ไขได้ [FieldType](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime12](./get_datetime12/)() | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดไว้เป็นอันดับสิบสอง (hh:mm AM/PM สำหรับภาษาอังกฤษ) ไม่สามารถแก้ไขได้ [FieldType](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime13](./get_datetime13/)() | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดไว้เป็นอันดับสิบสาม (hh:mm:ss AM/PM สำหรับภาษาอังกฤษ) ไม่สามารถแก้ไขได้ [FieldType](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime2](./get_datetime2/)() | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดไว้เป็นอันดับสอง (Day, Month DD, YYYY สำหรับภาษาอังกฤษ) ไม่สามารถแก้ไขได้ [FieldType](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime3](./get_datetime3/)() | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดไว้เป็นอันดับสาม (DD Month YYYY สำหรับภาษาอังกฤษ) ไม่สามารถแก้ไขได้ [FieldType](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime4](./get_datetime4/)() | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดไว้เป็นอันดับสี่ (Month DD, YYYY สำหรับภาษาอังกฤษ) ไม่สามารถแก้ไขได้ [FieldType](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime5](./get_datetime5/)() | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดไว้เป็นอันดับห้า (DD-Mon-YY สำหรับภาษาอังกฤษ) ไม่สามารถแก้ไขได้ [FieldType](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime6](./get_datetime6/)() | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดไว้เป็นอันดับหก (Month YY สำหรับภาษาอังกฤษ) ไม่สามารถแก้ไขได้ [FieldType](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime7](./get_datetime7/)() | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดไว้เป็นอันดับเจ็ด (Mon-YY สำหรับภาษาอังกฤษ) ไม่สามารถแก้ไขได้ [FieldType](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime8](./get_datetime8/)() | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดไว้เป็นอันดับแปด (MM/DD/YYYY hh:mm AM/PM สำหรับภาษาอังกฤษ) ไม่สามารถแก้ไขได้ [FieldType](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_DateTime9](./get_datetime9/)() | วันที่และเวลาปัจจุบันในรูปแบบที่กำหนดไว้เป็นอันดับเก้า (MM/DD/YYYY hh:mm:ss AM/PM สำหรับภาษาอังกฤษ) ไม่สามารถแก้ไขได้ [FieldType](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_Footer](./get_footer/)() | ส่วนท้ายของ [Slide](../slide/) ไม่สามารถแก้ไขได้ [FieldType](./) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_Header](./get_header/)() | ส่วนหัวของ [Slide](../slide/) ไม่สามารถแก้ไขได้ [FieldType](./) |
| [System::String](../../system/string/) [get_InternalString](./get_internalstring/)() override | คืนชื่อภายในของอ็อบเจกต์ [FieldType](./) นี้ อ่าน [System::String](../../system/string/) |
| static [System::SharedPtr](../../system/sharedptr/)\<[FieldType](./)\> [get_SlideNumber](./get_slidenumber/)() | หมายเลขสไลด์ปัจจุบัน ไม่สามารถแก้ไขได้ [FieldType](./) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| **int32_t** [GetHashCode](./gethashcode/)() const override | คืนค่า hashcode ของอ็อบเจกต์นี้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์ เป็นการเทียบกับการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C# |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เทียบกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบกับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# เปิดใช้งานการโคลนประเภทกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสำเนาคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสำเนาคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_InternalString](./set_internalstring/)([System::String](../../system/string/)) override | คืนชื่อภายในของอ็อบเจกต์ [FieldType](./) นี้ เขียน [System::String](../../system/string/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared) อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบกับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C# เปิดใช้งานการแปลงอ็อบเจกต์กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการดำเนินการ typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IFieldType](../ifieldtype/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)