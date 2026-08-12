---
title: IChartPlotArea
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนของคุณสมบัติหัวเรื่องแผนภูมิ
type: docs
weight: 794
url: /th/aspose.slides.charts/ichartplotarea/
---
## IChartPlotArea คลาส

เป็นตัวแทนของคุณสมบัติหัวเรื่องแผนภูมิ

```cpp
class IChartPlotArea : public Aspose::Slides::Charts::ILayoutable,
                       public Aspose::Slides::Charts::IActualLayout
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ NaN สองค่าโดยถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ NaN สองค่าโดยถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | ระบุความสูงจริงขององค์ประกอบแผนภูมิ เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง อ่าน **float** |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | ระบุความกว้างจริงขององค์ประกอบแผนภูมิ เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง อ่าน **float** |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | ระบุตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง อ่าน **float** |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง อ่าน **float** |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | รับค่าตำแหน่งบนขององค์ประกอบแผนภูมิเป็นส่วนของความสูงของแผนภูมิ อ่านอย่างเดียว **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | ส่งคืนแผนภูมิ อ่านอย่างเดียว [IChart](../ichart/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | ส่งคืนรูปแบบของพื้นที่พล็อต อ่านอย่างเดียว [IFormat](../iformat/) |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | ระบุความสูงขององค์ประกอบแผนภูมิเป็นส่วนของความสูงของแผนภูมิ อ่าน **float** |
| virtual [Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/) [get_LayoutTargetType](./get_layouttargettype/)() | หากการจัดเรียงของพื้นที่พล็อตกำหนดด้วยตนเอง คุณสมบัตินี้ระบุว่าจัดเรียงพื้นที่พล็อตโดยภายใน (ไม่รวมแกนและป้ายแกน) หรือโดยภายนอก (รวมแกนและป้ายแกน) อ่าน [LayoutTargetType](../layouttargettype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | ส่งคืนการนำเสนอ อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/) |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | รับค่าขวาขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างของแผนภูมิ อ่านอย่างเดียว **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | ส่งคืนสไลด์ฐาน อ่านอย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/) |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | ระบุความกว้างขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างของแผนภูมิ อ่าน **float** |
| virtual **float** [get_X](../ilayoutable/get_x/)() | ระบุตำแหน่ง x (ซ้าย) ขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างของแผนภูมิ อ่าน **float** |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | ระบุตำแหน่งบนขององค์ประกอบแผนภูมิเป็นส่วนของความสูงของแผนภูมิ อ่าน **float** |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเทียบเคียงของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการสร้างแฮชของอ็อบเจกต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์ เป็นเทียบเคียงของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType เป็นเทียบเคียงของตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อคตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเทียบเคียงของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรเลย จริง ๆ แล้วเพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์มอบหมาย ไม่ได้คัดลอกอะไรเลย จริง ๆ แล้วเพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | ระบุความสูงขององค์ประกอบแผนภูมิเป็นส่วนของความสูงของแผนภูมิ เขียน **float** |
| virtual void [set_LayoutTargetType](./set_layouttargettype/)([Aspose::Slides::Charts::LayoutTargetType](../layouttargettype/)) | หากการจัดเรียงของพื้นที่พล็อตกำหนดด้วยตนเอง คุณสมบัตินี้ระบุว่าจัดเรียงพื้นที่พล็อตโดยภายใน (ไม่รวมแกนและป้ายแกน) หรือโดยภายนอก (รวมแกนและป้ายแกน) เขียน [LayoutTargetType](../layouttargettype/) |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | ระบุความกว้างขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างของแผนภูมิ เขียน **float** |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | ระบุตำแหน่ง x (ซ้าย) ขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างของแผนภูมิ เขียน **float** |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | ระบุตำแหน่งบนขององค์ประกอบแผนภูมิเป็นส่วนของความสูงของแผนภูมิ เขียน **float** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared) อนุญาตเปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเทียบเคียงของเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เป็นการปลดล็อคตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [ILayoutable](../ilayoutable/)
* คลาส [IActualLayout](../iactuallayout/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)