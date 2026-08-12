---
title: LineFormat
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทนรูปแบบของเส้น.
type: docs
weight: 4382
url: /th/aspose.slides/lineformat/
---
## LineFormat คลาส

แทนรูปแบบของเส้น

```cpp
class LineFormat : public Aspose::Slides::PVIObject,
                   public Aspose::Slides::ILineFormat
```

## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override |  |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\>) override | กำหนดว่าตัวอย่างสอง [LineFormat](./) เท่ากันหรือไม่ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบอ้างอิงตามสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมในรูปแบบ C# ซึ่ง NaN สองค่าถูกพิจารณาเท่ากันแม้ว่า IEC 60559:1989 กำหนดว่า NaN ไม่เท่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมในรูปแบบ C# ซึ่ง NaN สองค่าถูกพิจารณาเท่ากันแม้ว่า IEC 60559:1989 กำหนดว่า NaN ไม่เท่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() override | คืนค่าการจัดตำแหน่งเส้น. อ่าน [LineAlignment](../linealignment/) |
| [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() override | คืนค่าความยาวหัวลูกศรที่จุดเริ่มต้นของเส้น. อ่าน [LineArrowheadLength](../linearrowheadlength/) |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() override | คืนค่าสไตล์หัวลูกศรที่จุดเริ่มต้นของเส้น. อ่าน [LineArrowheadStyle](../linearrowheadstyle/) |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() override | คืนค่าความกว้างหัวลูกศรที่จุดเริ่มต้นของเส้น. อ่าน [LineArrowheadWidth](../linearrowheadwidth/) |
| [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() override | คืนค่าสไตล์การปิดปลายเส้น. อ่าน [LineCapStyle](../linecapstyle/) |
| [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() override | คืนค่ารูปแบบจุดทับแบบกำหนดเอง. อ่าน **float**[] |
| [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() override | คืนค่าสไตล์จุดทับของเส้น. อ่าน [LineDashStyle](../linedashstyle/) |
| [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() override | คืนค่าความยาวหัวลูกศรที่ส่วนท้ายของเส้น. อ่าน [LineArrowheadLength](../linearrowheadlength/) |
| [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() override | คืนค่าสไตล์หัวลูกศรที่ส่วนท้ายของเส้น. อ่าน [LineArrowheadStyle](../linearrowheadstyle/) |
| [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() override | คืนค่าความกว้างหัวลูกศรที่ส่วนท้ายของเส้น. อ่าน [LineArrowheadWidth](../linearrowheadwidth/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormat](../ilinefillformat/)\> [get_FillFormat](./get_fillformat/)() override | คืนค่ารูปแบบการเติมของเส้น. อ่านอย่างเดียว [ILineFillFormat](../ilinefillformat/) |
| **bool** [get_IsFormatNotDefined](./get_isformatnotdefined/)() override | คืนค่า true หากรูปแบบเส้นไม่ได้กำหนด (เช่น เพิ่งสร้าง, ค่าเริ่มต้น) อ่านอย่างเดียว **bool** |
| [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() override | คืนค่าสไตล์การเชื่อมต่อของเส้น. อ่าน [LineJoinStyle](../linejoinstyle/) |
| **float** [get_MiterLimit](./get_miterlimit/)() override | คืนค่าขีดจำกัดมิตเตอร์ของเส้น. อ่าน **float** |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | คืนค่าอ็อบเจ็กต์ Parent_Immediate. อ่านอย่างเดียว [IDOMObject](../idomobject/) |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | คืนค่าพาเรนท์ [IPresentationComponent](../ipresentationcomponent/). อ่านอย่างเดียว [IPresentationComponent](../ipresentationcomponent/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormat](../isketchformat/)\> [get_SketchFormat](./get_sketchformat/)() override | คืนค่ารูปแบบสเก็ตช์ของเส้น. อ่านอย่างเดียว [ILineFillFormat](../ilinefillformat/) |
| [LineStyle](../linestyle/) [get_Style](./get_style/)() override | คืนค่าสไตล์ของเส้น. อ่าน [LineStyle](../linestyle/) |
| **double** [get_Width](./get_width/)() override | คืนค่าความกว้างของเส้น. อ่าน **double** |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมกับอ็อบเจ็กต์ |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](../ilineformateffectivedata/)\> [GetEffective](./geteffective/)() override | ดึงข้อมูลการจัดรูปแบบเส้นที่มีผลโดยใช้การสืบทอด |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | คืนค่ารหัสแฮช |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของอ็อบเจ็กต์. เป็นแบบจำลองของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นแบบจำลองของตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบจำลองของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคัดลอกประเภทแบบกำหนดเอง |
|  [Object](../../system/object/object/)() |  |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_Alignment](./set_alignment/)([LineAlignment](../linealignment/)) override | ตั้งค่าการจัดตำแหน่งเส้น. เขียน [LineAlignment](../linealignment/) |
| void [set_BeginArrowheadLength](./set_beginarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | ตั้งค่าความยาวหัวลูกศรที่จุดเริ่มต้นของเส้น. เขียน [LineArrowheadLength](../linearrowheadlength/) |
| void [set_BeginArrowheadStyle](./set_beginarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | ตั้งค่าสไตล์หัวลูกศรที่จุดเริ่มต้นของเส้น. เขียน [LineArrowheadStyle](../linearrowheadstyle/) |
| void [set_BeginArrowheadWidth](./set_beginarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | ตั้งค่าความกว้างหัวลูกศรที่จุดเริ่มต้นของเส้น. เขียน [LineArrowheadWidth](../linearrowheadwidth/) |
| void [set_CapStyle](./set_capstyle/)([LineCapStyle](../linecapstyle/)) override | ตั้งค่าสไตล์การปิดปลายเส้น. เขียน [LineCapStyle](../linecapstyle/) |
| void [set_CustomDashPattern](./set_customdashpattern/)([System::ArrayPtr](../../system/arrayptr/)\<**float**\>) override | ตั้งค่ารูปแบบจุดทับแบบกำหนดเอง. เขียน **float**[] |
| void [set_DashStyle](./set_dashstyle/)([LineDashStyle](../linedashstyle/)) override | ตั้งค่าสไตล์จุดทับของเส้น. เขียน [LineDashStyle](../linedashstyle/) |
| void [set_EndArrowheadLength](./set_endarrowheadlength/)([LineArrowheadLength](../linearrowheadlength/)) override | ตั้งค่าความยาวหัวลูกศรที่ส่วนท้ายของเส้น. เขียน [LineArrowheadLength](../linearrowheadlength/) |
| void [set_EndArrowheadStyle](./set_endarrowheadstyle/)([LineArrowheadStyle](../linearrowheadstyle/)) override | ตั้งค่าสไตล์หัวลูกศรที่ส่วนท้ายของเส้น. เขียน [LineArrowheadStyle](../linearrowheadstyle/) |
| void [set_EndArrowheadWidth](./set_endarrowheadwidth/)([LineArrowheadWidth](../linearrowheadwidth/)) override | ตั้งค่าความกว้างหัวลูกศรที่ส่วนท้ายของเส้น. เขียน [LineArrowheadWidth](../linearrowheadwidth/) |
| void [set_JoinStyle](./set_joinstyle/)([LineJoinStyle](../linejoinstyle/)) override | ตั้งค่าสไตล์การเชื่อมต่อของเส้น. เขียน [LineJoinStyle](../linejoinstyle/) |
| void [set_MiterLimit](./set_miterlimit/)(**float**) override | ตั้งค่าขีดจำกัดมิตเตอร์ของเส้น. เขียน **float** |
| void [set_Style](./set_style/)([LineStyle](../linestyle/)) override | ตั้งค่าสไตล์ของเส้น. เขียน [LineStyle](../linestyle/) |
| void [set_Width](./set_width/)(**double**) override | ตั้งค่าความกว้างของเส้น. เขียน **double** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared). เปิดให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์ขึ้น. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าจำนวนอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแบบจำลองของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามคอนสตรัคต์ typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak ขึ้น. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak ลง. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## See Also

* คลาส [PVIObject](../pviobject/)
* คลาส [ILineFormat](../ilineformat/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)