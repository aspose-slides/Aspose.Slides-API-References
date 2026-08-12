---
title: IDataLabel
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เป็นตัวแทนของป้ายชื่อชุดข้อมูล
type: docs
weight: 937
url: /th/aspose.slides.charts/idatalabel/
---
## IDataLabel คลาส

แสดงฉลากของชุดข้อมูล.

```cpp
class IDataLabel : public Aspose::Slides::Charts::ILayoutable,
                   public Aspose::Slides::Charts::IOverridableText,
                   public Aspose::Slides::Charts::IActualLayout
```

## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ \"text\". หาก TextFrameForOverriding ได้รับการเริ่มต้นแล้วจะทำการเปลี่ยนข้อความของมันเท่านั้น. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ซึ่ง NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ซึ่ง NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุภายในเท่านั้น. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | ระบุความสูงจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | ระบุความกว้างจริงขององค์ประกอบแผนภูมิ. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | ระบุตำแหน่ง x จริง (ด้านซ้าย) ขององค์ประกอบแผนภูมิเพื่อเทียบกับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | ระบุตำแหน่งบนจริงขององค์ประกอบแผนภูมิเพื่อเทียบกับมุมซ้ายบนของแผนภูมิ. เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | รับตำแหน่งบนขององค์ประกอบแผนภูมิเป็นส่วนของความสูงของแผนภูมิ. อ่าน-อย่างเดียว **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | ส่งคืนแผนภูมิ. อ่าน-อย่างเดียว [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDataLabelFormat](../idatalabelformat/)\> [get_DataLabelFormat](./get_datalabelformat/)() | ส่งคืนรูปแบบของป้ายข้อมูล. อ่าน-อย่างเดียว [IDataLabelFormat](../idatalabelformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | ระบุความสูงขององค์ประกอบแผนภูมิเป็นส่วนของความสูงของแผนภูมิ. อ่าน **float**. |
| virtual **bool** [get_IsVisible](./get_isvisible/)() | ค่า False หมายความว่าป้ายข้อมูลไม่ปรากฏ (และทั้งหมด Show*-flags (ShowValue, ...) จะเป็น false). อ่าน-อย่างเดียว **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | ส่งคืนการนำเสนอ. อ่าน-อย่างเดียว [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | รับตำแหน่งขวาขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างของแผนภูมิ. อ่าน-อย่างเดียว **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | ส่งคืนสไลด์ฐาน. อ่าน-อย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | ส่งคืนรูปแบบข้อความของแผนภูมิ. อ่าน-อย่างเดียว [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | สามารถบรรจุข้อความที่จัดรูปแบบอย่างละเอียด. หาก property นี้ไม่เป็น null ค่าข้อความที่จัดรูปแบบนี้จะครอบคลุมข้อความที่สร้างโดยอัตโนมัติ. ข้อความที่สร้างโดยอัตโนมัติเป็น property แฝงของป้ายข้อมูล, ป้ายหน่วยของแกนค่า, ชื่อแกน, ชื่อแผนภูมิ, ป้ายของเส้นแนวโน้ม. ข้อความที่สร้างโดยอัตโนมัติได้รับการจัดรูปแบบด้วย property [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/). อ่าน-อย่างเดียว [ITextFrame](../../aspose.slides/itextframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\> [get_ValueFromCell](./get_valuefromcell/)() | รับเซลล์ข้อมูลของ workbook. ใช้เมื่อ IDataLabelFormat::get(set)_ShowLabelValueFromCell มีค่า true. |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | ระบุความกว้างขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างของแผนภูมิ. อ่าน **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | ระบุตำแหน่ง x (ด้านซ้าย) ขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างของแผนภูมิ. อ่าน **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | ระบุตำแหน่งบนขององค์ประกอบแผนภูมิเป็นส่วนของความสูงของแผนภูมิ. อ่าน **float**. |
| virtual [System::String](../../system/string/) [GetActualLabelText](./getactuallabeltext/)() | ส่งคืนข้อความป้ายจริงตามการตั้งค่า [DataLabelFormat](../datalabelformat/) หรือค่าของ TextFrameForOverriding.Text. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแนวคิดคล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้การแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นแนวคิดคล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual void [Hide](./hide/)() | ทำให้ป้ายข้อมูลซ่อนโดยตั้งค่า Show*-flags ทั้งหมด (ShowValue, ...) เป็น false. IsVisible จะเป็น false หลังจากนี้. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่ระบุโดย targetType หรือไม่. เป็นแนวคิดคล้ายออเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแนวคิดคล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้การทำสำเนาชนิดที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | เป็นการเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | เป็นการเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | ระบุความสูงขององค์ประกอบแผนภูมิเป็นส่วนของความสูงของแผนภูมิ. เขียน **float**. |
| virtual void [set_ValueFromCell](./set_valuefromcell/)([System::SharedPtr](../../system/sharedptr/)\<[IChartDataCell](../ichartdatacell/)\>) | ตั้งค่าเซลล์ข้อมูลของ workbook. ใช้เมื่อ IDataLabelFormat::get(set)_ShowLabelValueFromCell มีค่า true. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | ระบุความกว้างขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างของแผนภูมิ. เขียน **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | ระบุตำแหน่ง x (ด้านซ้าย) ขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างของแผนภูมิ. เขียน **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | ระบุตำแหน่งบนขององค์ประกอบแผนภูมิเป็นส่วนของความสูงของแผนภูมิ. เขียน **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแนวคิดคล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้การแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการจำลองโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [ILayoutable](../ilayoutable/)
* คลาส [IOverridableText](../ioverridabletext/)
* คลาส [IActualLayout](../iactuallayout/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)