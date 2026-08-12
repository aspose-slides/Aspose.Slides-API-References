---
title: ChartDataWorksheet
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงแผ่นงานที่เชื่อมโยงกับ IChartDataCell
type: docs
weight: 209
url: /th/aspose.slides.charts/chartdataworksheet/
---
## ChartDataWorksheet คลาส


แสดงถึงแผ่นงานที่เชื่อมโยงกับ [IChartDataCell](../ichartdatacell/)

```cpp
class ChartDataWorksheet : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::Charts::ChartDataWorksheetCollection>>,
                           public Aspose::Slides::Charts::IChartDataWorksheet
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C#-style ที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| **int32_t** [get_Index](./get_index/)() override | รับดัชนีของแผ่นงาน. อ่านอย่างเดียว **int32_t**. |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | คืนค่าชื่อของแผ่นงาน. อ่านอย่างเดียว [System::String](../../system/string/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด [Object.GetHashCode()](../../system/object/gethashcode/) ของ C#. ทำให้สามารถแฮชอ็อบเจ็กต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ คล้ายกับการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# สำหรับการล็อก. เรียกใช้โดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C#. ทำให้สามารถโคลนประเภทกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สามารถคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สามารถคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์ด้วยการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์ด้วยการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงของอ็อบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะรูปแบบของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะรูปแบบของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงแชร์ลงตามค่าที่ระบุ. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | กำหนดอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่เป็น shared). ทำให้สามารถเปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงแชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงแชร์ ไม่ควรเรียกโดยตรง; ให้ใช้สมัรท์พอยน์เตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงแชร์ ไม่ควรเรียกโดยตรง; ให้ใช้สมัรท์พอยน์เตอร์หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C#. ทำให้สามารถแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# สำหรับการปลดล็อก. เรียกใช้โดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิง weak ไม่ควรเรียกโดยตรง; ให้ใช้สมัรท์พอยน์เตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิง weak ไม่ควรเรียกโดยตรง; ให้ใช้สมัรท์พอยน์เตอร์หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [DomObject](../../aspose.slides/domobject/)
* คลาส [IChartDataWorksheet](../ichartdataworksheet/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)