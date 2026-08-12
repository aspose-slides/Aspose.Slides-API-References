---
title: IChartTitle
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงคุณสมบัติของชื่อแผนภูมิ.
type: docs
weight: 911
url: /th/aspose.slides.charts/icharttitle/
---
## IChartTitle คลาส

แสดงคุณสมบัติของชื่อแผนภูมิ.

```cpp
class IChartTitle : public Aspose::Slides::Charts::ILayoutable,
                    public Aspose::Slides::Charts::IOverridableText,
                    public Aspose::Slides::Charts::IActualLayout
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [AddTextFrameForOverriding](../ioverridabletext/addtextframeforoverriding/)([System::String](../../system/string/)) | เริ่มต้น TextFrameForOverriding ด้วยข้อความในพารามิเตอร์ "text" หาก TextFrameForOverriding ถูกเริ่มต้นแล้วจะเปลี่ยนข้อความของมันเท่านั้น. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่สอง NaN จะถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่สอง NaN จะถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual **float** [get_ActualHeight](../iactuallayout/get_actualheight/)() | ระบุความสูงจริงขององค์ประกอบแผนภูมิ เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| virtual **float** [get_ActualWidth](../iactuallayout/get_actualwidth/)() | ระบุความกว้างจริงขององค์ประกอบแผนภูมิ เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| virtual **float** [get_ActualX](../iactuallayout/get_actualx/)() | ระบุตำแหน่ง x จริง (ซ้าย) ขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| virtual **float** [get_ActualY](../iactuallayout/get_actualy/)() | ระบุด้านบนจริงขององค์ประกอบแผนภูมิสัมพันธ์กับมุมซ้ายบนของแผนภูมิ เรียกเมธอด [IChart::ValidateChartLayout](../ichart/validatechartlayout/) ก่อนเพื่อรับค่าจริง. อ่าน **float**. |
| virtual **float** [get_Bottom](../ilayoutable/get_bottom/)() | รับค่าด้านบนขององค์ประกอบแผนภูมิเป็นส่วนของความสูงแผนภูมิ อ่านอย่างเดียว **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChart](../ichart/)\> [get_Chart](../ichartcomponent/get_chart/)() | คืนค่าแผนภูมิ. อ่านอย่างเดียว [IChart](../ichart/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFormat](../iformat/)\> [get_Format](./get_format/)() | คืนค่าสไตล์การเติม สีเส้น และเอฟเฟกต์ของชื่อเรื่อง. อ่านอย่างเดียว [IFormat](../iformat/). |
| virtual **float** [get_Height](../ilayoutable/get_height/)() | ระบุความสูงขององค์ประกอบแผนภูมิเป็นส่วนของความสูงแผนภูมิ อ่าน **float**. |
| virtual **bool** [get_Overlay](./get_overlay/)() | กำหนดว่าจะอนุญาตให้องค์ประกอบแผนภูมิอื่นทับชื่อเรื่องหรือไม่ อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | คืนค่าการนำเสนอ. อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/). |
| virtual **float** [get_Right](../ilayoutable/get_right/)() | รับค่าขวาขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างแผนภูมิ อ่านอย่างเดียว **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | คืนค่า slide พื้นฐานอ่านอย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IChartTextFormat](../icharttextformat/)\> [get_TextFormat](../iformattedtextcontainer/get_textformat/)() | คืนรูปแบบข้อความแผนภูมิอ่านอย่างเดียว [IChartTextFormat](../icharttextformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrameForOverriding](../ioverridabletext/get_textframeforoverriding/)() | สามารถมีข้อความที่จัดรูปแบบแบบ rich ได้ หากคุณสมบัตินี้ไม่เป็น null ค่าข้อความที่จัดรูปแบบนี้จะเขียนทับข้อความที่สร้างอัตโนมัติ ข้อความที่สร้างอัตโนมัติเป็นคุณสมบัติโดยอัตโนมัติของป้ายข้อมูล ป้ายหน่วยแสดงของแกนค่า ชื่อแกน ชื่อแผนภูมิ ป้ายของเส้นแนวโน้ม ข้อความที่สร้างอัตโนมัติถูกจัดรูปแบบด้วยคุณสมบัติ [IFormattedTextContainer::get_TextFormat](../iformattedtextcontainer/get_textformat/) อ่านอย่างเดียว [ITextFrame](../../aspose.slides/itextframe/). |
| virtual **float** [get_Width](../ilayoutable/get_width/)() | ระบุความกว้างขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างแผนภูมิ อ่าน **float**. |
| virtual **float** [get_X](../ilayoutable/get_x/)() | ระบุตำแหน่ง x (ซ้าย) ขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างแผนภูมิ อ่าน **float**. |
| virtual **float** [get_Y](../ilayoutable/get_y/)() | ระบุด้านบนขององค์ประกอบแผนภูมิเป็นส่วนของความสูงแผนภูมิ อ่าน **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมกับออบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชออบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์ อเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ อเนกประสงค์ของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เหมือนคำสั่ง lock() ของ C# สำหรับการล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไร จริง ๆ แล้วเพียงเริ่มต้นออบเจ็กต์ใหม่และอนุญาตให้สร้างสำเนาในซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไร จริง ๆ แล้วเพียงเริ่มต้นออบเจ็กต์ใหม่และอนุญาตให้สร้างสำเนาในซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | ความเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | ความเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมโดยค่าที่ระบุ. |
| virtual void [set_Height](../ilayoutable/set_height/)(**float**) | ระบุความสูงขององค์ประกอบแผนภูมิเป็นส่วนของความสูงแผนภูมิ เขียน **float**. |
| virtual void [set_Overlay](./set_overlay/)(**bool**) | กำหนดว่าจะอนุญาตให้องค์ประกอบแผนภูมิอื่นทับชื่อเรื่องหรือไม่ เขียน **bool**. |
| virtual void [set_Width](../ilayoutable/set_width/)(**float**) | ระบุความกว้างขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างแผนภูมิ เขียน **float**. |
| virtual void [set_X](../ilayoutable/set_x/)(**float**) | ระบุตำแหน่ง x (ซ้าย) ขององค์ประกอบแผนภูมิเป็นส่วนของความกว้างแผนภูมิ เขียน **float**. |
| virtual void [set_Y](../ilayoutable/set_y/)(**float**) | ระบุด้านบนขององค์ประกอบแผนภูมิเป็นส่วนของความสูงแผนภูมิ เขียน **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | กำหนดอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared) ทำให้สามารถสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่า ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อเนกประสงค์ของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงออบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เหมือนการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เหมือนการปลดล็อกของคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [ILayoutable](../ilayoutable/)
* คลาส [IOverridableText](../ioverridabletext/)
* คลาส [IActualLayout](../iactuallayout/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)