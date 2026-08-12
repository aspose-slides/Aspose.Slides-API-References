---
title: DataLabel
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนของป้ายกำกับซีรีส์
type: docs
weight: 365
url: /th/aspose.slides.charts/datalabel/
---
## DataLabel คลาส

Represents a series labels.

```cpp
class DataLabel : public Aspose::Slides::Charts::IDataLabel,
                  public Aspose::Slides::IDOMObject
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ \"text\". หาก TextFrameForOverriding ได้รับการเริ่มต้นแล้วจะทำการเปลี่ยนข้อความของมันเท่านั้น. |
|  [DataLabel](./datalabel/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataPoint](../ichartdatapoint/)\>) | สร้างอินสแตนซ์ใหม่ของคลาส [DataLabel](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจำนวนทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจำนวนทศนิยมแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น. |
| **float** [get_ActualHeight](./get_actualheight/)() override | ระบุความสูงจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | ระบุความกว้างจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| **float** [get_ActualX](./get_actualx/)() override | ระบุตำแหน่ง x จริง (ด้านซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| **float** [get_ActualY](./get_actualy/)() override | ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| **float** [get_Bottom](./get_bottom/)() override | ด้านล่าง. อ่านอย่างเดียว **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | ส่งคืนแผนภูมิแม่. อ่านอย่างเดียว [IChart](../ichart/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() override | ส่งคืนรูปแบบป้ายกำกับข้อมูล. อ่านอย่างเดียว [IDataLabelFormat](../idatalabelformat/). |
| **float** [get_Height](./get_height/)() override | ส่งคืนความสูงของหัวเรื่องเป็นส่วนของความสูงแผนภูมิ. อ่าน **float**. |
| **bool** [get_IsVisible](./get_isvisible/)() override | ค่า False หมายความว่าป้ายกำกับข้อมูลไม่แสดง (และเครื่องหมาย Show*-flags ทั้งหมด (ShowValue, ...) จะเป็น false). อ่านอย่างเดียว **bool**. |
| **float** [get_Right](./get_right/)() override | ด้านขวา. อ่านอย่างเดียว **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | ส่งคืนรูปแบบข้อความ. อ่านอย่างเดียว [IChartTextFormat](../icharttextformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | สามารถบรรจุข้อความที่มีการจัดรูปแบบแบบ rich ได้. หากคุณสมบัตินี้ไม่เป็น null แล้วค่าข้อความที่จัดรูปแบบนี้จะทับข้อความที่สร้างโดยอัตโนมัติของป้ายกำกับข้อมูล. ข้อความที่สร้างโดยอัตโนมัติของป้ายกำกับข้อมูลหมายถึงข้อความที่จัดการโดยคุณสมบัติ ShowSeriesName, ShowValue, ... และถูกจัดรูปแบบด้วยคุณสมบัติ TextFormatManager.TextFormat. อ่านอย่างเดียว [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() override | รับเซลล์ข้อมูลของ workbook. ใช้หากคุณสมบัติ IDataLabelFormat::get(set)_ShowLabelValueFromCell มีค่าเป็น true. |
| **float** [get_Width](./get_width/)() override | ส่งคืนความกว้างของหัวเรื่องเป็นส่วนของความกว้างแผนภูมิ. อ่าน **float**. |
| **float** [get_X](./get_x/)() override | ส่งคืนพิกัด x ของหัวเรื่องเป็นส่วนของความกว้างแผนภูมิ. อ่าน **float**. |
| **float** [get_Y](./get_y/)() override | ส่งคืนพิกัด y ของหัวเรื่องเป็นส่วนของความสูงแผนภูมิ. อ่าน **float**. |
| [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() override | ส่งคืนข้อความป้ายกำกับจริงตามการตั้งค่า [DataLabelFormat](../datalabelformat/) หรือค่าของ [get_TextFrameForOverriding()](./get_textframeforoverriding/)->get(set)_Text(). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ช่วยทำแฮชของอ็อบเจกต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| void [Hide](./hide/)() override | ทำให้ป้ายกำกับข้อมูลซ่อนโดยตั้งค่า Show*-flags ทั้งหมด (ShowValue, ...) ให้เป็นสถานะ false. IsVisible จะเป็น false หลังจากนี้. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอเนกประสงค์ของออปเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ช่วยทำการโคลนนิ่งของประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสำเนาคอนสตรัคเตอร์ของคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสำเนาคอนสตรัคเตอร์ของคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่ากับ nullptr ด้วยการอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_Height](./set_height/)(**float**) override | ตั้งค่าความสูงของหัวเรื่องเป็นส่วนของความสูงแผนภูมิ. เขียน **float**. |
| void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) override | ตั้งค่าเซลล์ข้อมูลของ workbook. ใช้หากคุณสมบัติ IDataLabelFormat::get(set)_ShowLabelValueFromCell มีค่าเป็น true. |
| void [set_Width](./set_width/)(**float**) override | ตั้งค่าความกว้างของหัวเรื่องเป็นส่วนของความกว้างแผนภูมิ. เขียน **float**. |
| void [set_X](./set_x/)(**float**) override | ตั้งค่าพิกัด x ของหัวเรื่องเป็นส่วนของความกว้างแผนภูมิ. เขียน **float**. |
| void [set_Y](./set_y/)(**float**) override | ตั้งค่าพิกัด y ของหัวเรื่องเป็นส่วนของความสูงแผนภูมิ. เขียน **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.ToString()](../../system/object/tostring/). ช่วยแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IDataLabel](../idatalabel/)
* คลาส [IDOMObject](../../aspose.slides/idomobject/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)