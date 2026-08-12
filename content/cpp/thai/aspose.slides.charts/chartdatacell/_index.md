---
title: ChartDataCell
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงเซลล์สำหรับข้อมูลแผนภูมิ.
type: docs
weight: 131
url: /th/aspose.slides.charts/chartdatacell/
---
## คลาส ChartDataCell

แสดงถึงเซลล์สำหรับข้อมูลแผนภูมิ

```cpp
class ChartDataCell : public Aspose::Slides::Charts::IChartDataCell
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| void [Calculate](./calculate/)(**bool**) override | ถ้าเซลล์มีสูตร ค่าจะถูกอัปเดตตามสูตรนั้น. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยในสไตล์ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยในสไตล์ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataWorksheet](../ichartdataworksheet/)\> [get_ChartDataWorksheet](./get_chartdataworksheet/)() override | ดึง worksheet. อ่านอย่างเดียว [IChartDataWorksheet](../ichartdataworksheet/). |
| **int32_t** [get_Column](./get_column/)() override | คืนค่าดัชนีของคอลัมน์ใน worksheet ที่เซลล์ตั้งอยู่. อ่านอย่างเดียว **int32_t**. |
| [System::String](../../system/string/) [get_CustomNumberFormat](./get_customnumberformat/)() override | ดึงรูปแบบการแสดงผลที่กำหนดเองของตัวเลขและวันที่. หากค่าเป็นค่าว่างจะใช้ค่า PresetNumberFormat. อ่าน [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_Formula](./get_formula/)() override | ดึงสูตรในสไตล์ A1. |
| **bool** [get_IsHidden](./get_ishidden/)() override | กำหนดว่าเซลล์ถูกซ่อนหรือไม่. อ่านอย่างเดียว **bool**. |
| **uint8_t** [get_PresetNumberFormat](./get_presetnumberformat/)() override | ดึงรูปแบบการแสดงผลที่มีมาในของตัวเลขและวันที่. หมายเลขที่ตั้งค่าต้องอยู่ในช่วง [0..22] หรือ [37..49]. อ่าน **uint8_t**. |
| [System::String](../../system/string/) [get_R1C1Formula](./get_r1c1formula/)() override | ดึงสูตรในสไตล์ R1C1. |
| **int32_t** [get_Row](./get_row/)() override | คืนค่าดัชนีของแถวใน worksheet ที่เซลล์ตั้งอยู่. อ่านอย่างเดียว **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() override | ดึงค่าของเซลล์. อ่าน [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอะแนโละของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของอ็อบเจ็กต์. เป็นอะแนโละของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอะแนโละของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อคตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอะแนโละของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคล cloning ของประเภทที่กำหนดเอง. |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเชี่ยวชาญของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเชี่ยวชาญของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงร่วมลงตามค่าที่ระบุ. |
| void [set_CustomNumberFormat](./set_customnumberformat/)([System::String](../../system/string/)) override | ตั้งค่ารูปแบบการแสดงผลที่กำหนดเองของตัวเลขและวันที่. หากค่าเป็นค่าว่างจะใช้ค่า PresetNumberFormat. เขียน [System::String](../../system/string/). |
| void [set_Formula](./set_formula/)([System::String](../../system/string/)) override | ตั้งสูตรในสไตล์ A1. |
| void [set_PresetNumberFormat](./set_presetnumberformat/)(**uint8_t**) override | ตั้งค่ารูปแบบการแสดงผลที่มีมาในของตัวเลขและวันที่. หมายเลขที่ตั้งค่าต้องอยู่ในช่วง [0..22] หรือ [37..49]. เขียน **uint8_t**. |
| void [set_R1C1Formula](./set_r1c1formula/)([System::String](../../system/string/)) override | ตั้งสูตรในสไตล์ R1C1. |
| void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | ตั้งค่าของเซลล์. เขียน [System::Object](../../system/object/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอะแนโละของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อคตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิง weak. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิง weak. ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IChartDataCell](../ichartdatacell/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)