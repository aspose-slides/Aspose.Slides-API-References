---
title: StringConcat
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: ต่อสตริงเมื่อจำนวนสตริงไม่ทราบล่วงหน้า.
type: docs
weight: 1
url: /th/system.xml.xsl.runtime/stringconcat/
---
## StringConcat คลาส

ต่อสตริงเมื่อจำนวนสตริงไม่ทราบล่วงหน้า.

```cpp
class StringConcat : public System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
| void [Clear](./clear/)() | ล้างสตริงผลลัพธ์. |
| void [Concat](./concat/)(const [String](../../system/string/)\&) | ต่อสตริงใหม่เข้ากับผลลัพธ์. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ลักษณะการทำงานของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนลอยตัวสไตล์ C# ที่ NaN สองค่าเทียบเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนลอยตัวสไตล์ C# ที่ NaN สองค่าเทียบเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น. |
| [String](../../system/string/) [get_Delimiter](./get_delimiter/)() | ส่งคืนสตริงที่ใช้เป็นตัวคั่นสตริงที่ต่อกัน. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้การแฮชอ็อบเจ็กต์ที่กำหนดเอง. |
| [String](../../system/string/) [GetResult](./getresult/)() | ส่งคืนสตริงผลลัพธ์. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของอ็อบเจ็กต์. เทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เทียบเคียงกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามการล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้การโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรเลย จริง ๆ แล้วเพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างคอนสตรัคเตอร์คัดลอกของซับคลาสได้. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรเลย จริง ๆ แล้วเพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างคอนสตรัคเตอร์คัดลอกของซับคลาสได้. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | อ้างอิง-เปรียบเทียบอ็อบเจ็กต์แบบค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดลักษณะพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดลักษณะพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [set_Delimiter](./set_delimiter/)(const [String](../../system/string/)\&) | ตั้งค่าสตริงที่ใช้เป็นตัวคั่นสตริงที่ต่อกัน. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งค่าตัวนับการอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
|  [StringConcat](./stringconcat/)() | คอนสตรัคเตอร์เริ่มต้น. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้การแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามการสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามการปลดล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [System::Xml::Xsl::Runtime](../)
* ไลบรารี [Aspose.Slides](../../)