---
title: ChartTitle
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แสดงคุณสมบัติของชื่อแผนภูมิ
type: docs
weight: 326
url: /th/aspose.slides.charts/charttitle/
---
## ChartTitle คลาส


แสดงคุณสมบัติของชื่อแผนภูมิ

```cpp
class ChartTitle : public Aspose::Slides::Charts::IChartTitle,
                   public Aspose::Slides::IDOMObject
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](./addtextframeforoverriding/)([System::String](../../system/string/)) override | กำหนดค่า TextFrameForOverriding ด้วยข้อความที่อยู่ในพารามิเตอร์ \"text\". หาก TextFrameForOverriding ได้รับการกำหนดค่าแล้วจะทำการเปลี่ยนข้อความของมันเท่านั้น. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในรูปแบบของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในรูปแบบของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าแบบจุดลอยของ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าหมายเลขใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าแบบจุดลอยของ C# โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าหมายเลขใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้ภายในเท่านั้น. |
| **float** [get_ActualHeight](./get_actualheight/)() override | ระบุความสูงจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| **float** [get_ActualWidth](./get_actualwidth/)() override | ระบุความกว้างจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| **float** [get_ActualX](./get_actualx/)() override | ระบุตำแหน่ง x (ซ้าย) จริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| **float** [get_ActualY](./get_actualy/)() override | ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| **float** [get_Bottom](./get_bottom/)() override | ด้านล่าง. **float** แบบอ่านอย่างเดียว. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](./get_chart/)() override | ส่งคืนแผนภูมิมาโดยพาเรนท์. [IChart](../ichart/) แบบอ่านอย่างเดียว. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() override | ส่งคืนสไตล์การเติม, เส้น, เอฟเฟกต์ของชื่อ. [IFormat](../iformat/) แบบอ่านอย่างเดียว. |
| **float** [get_Height](./get_height/)() override | ส่งคืนความสูงของหัวเรื่องเป็นส่วนของความสูงของแผนภูมิ. อ่าน **float**. |
| **bool** [get_Overlay](./get_overlay/)() override | กำหนดว่าตัวองค์ประกอบแผนภูมิอื่น ๆ จะอนุญาตให้ทับหัวเรื่องหรือไม่. อ่าน **bool**. |
| **float** [get_Right](./get_right/)() override | ด้านขวา. **float** แบบอ่านอย่างเดียว. |
| [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](./get_textformat/)() override | ส่งคืนรูปแบบข้อความ. [IChartTextFormat](../icharttextformat/) แบบอ่านอย่างเดียว. |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](./get_textframeforoverriding/)() override | สามารถมีข้อความที่จัดรูปแบบอย่างสมบูรณ์. หากคุณสมบัตินี้ไม่เป็น null แล้วค่าข้อความที่จัดรูปแบบนี้จะทับข้อความที่สร้างโดยอัตโนมัติ. ข้อความที่สร้างโดยอัตโนมัติเป็นคุณสมบัติโดยอ้อมของป้ายกำกับข้อมูล, ป้ายกำหนดหน่วยแสดงของแกนค่า, ชื่อแกน, ชื่อแผนภูมิ, ป้ายกำหนดของเส้นแนวโน้ม. ข้อความที่สร้างโดยอัตโนมัติถูกจัดรูปแบบด้วยคุณสมบัติ [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). [ITextFrame](../../aspose.slides/itextframe/) แบบอ่านอย่างเดียว. |
| **float** [get_Width](./get_width/)() override | ส่งคืนความกว้างของหัวเรื่องเป็นส่วนของความกว้างของแผนภูมิ. อ่าน **float**. |
| **float** [get_X](./get_x/)() override | ส่งคืนพิกัด x ของหัวเรื่องเป็นส่วนของความกว้างของแผนภูมิ. อ่าน **float**. |
| **float** [get_Y](./get_y/)() override | ส่งคืนพิกัด y ของหัวเรื่องเป็นส่วนของความสูงของแผนภูมิ. อ่าน **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นออนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของวัตถุที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. เป็นออนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นออนาล็อกของตัวดำเนินการ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นออนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวคัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแต่เริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแต่เริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เป็นการเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เป็นการเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_Height](./set_height/)(**float**) override | ตั้งค่าความสูงของหัวเรื่องเป็นส่วนของความสูงของแผนภูมิ. เขียน **float**. |
| void [set_Overlay](./set_overlay/)(**bool**) override | กำหนดว่าตัวองค์ประกอบแผนภูมิอื่น ๆ จะอนุญาตให้ทับหัวเรื่องหรือไม่. เขียน **bool**. |
| void [set_Width](./set_width/)(**float**) override | ตั้งค่าความกว้างของหัวเรื่องเป็นส่วนของความกว้างของแผนภูมิ. เขียน **float**. |
| void [set_X](./set_x/)(**float**) override | ตั้งค่าพิกัด x ของหัวเรื่องเป็นส่วนของความกว้างของแผนภูมิ. เขียน **float**. |
| void [set_Y](./set_y/)(**float**) override | ตั้งค่าพิกัด y ของหัวเรื่องเป็นส่วนของความสูงของแผนภูมิ. เขียน **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์แม่แบบที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้เปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นออนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [IChartTitle](../icharttitle/)
* คลาส [IDOMObject](../../aspose.slides/idomobject/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)