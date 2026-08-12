---
title: ILineFormatEffectiveData
second_title: Aspose.Slides สำหรับ C++ API Reference
description: อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งมีคุณสมบัติการจัดรูปแบบบรรทัดที่ใช้ได้.
type: docs
weight: 2770
url: /th/aspose.slides/ilineformateffectivedata/
---
## ILineFormatEffectiveData คลาส

อ็อบเจกต์ที่ไม่เปลี่ยนแปลงซึ่งมีคุณสมบัติการจัดรูปแบบบรรทัดที่ใช้ได้

```cpp
class ILineFormatEffectiveData : public Aspose::Slides::ILineParamSource
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[ILineFormatEffectiveData](./)\>) | กำหนดว่าตัวอย่างสอง [ILineFormatEffectiveData](./) เท่ากันหรือไม่. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุกับใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบสไตล์ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบสไตล์ C# ที่ถือว่า NaN สองค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual [LineAlignment](../linealignment/) [get_Alignment](./get_alignment/)() | คืนค่าการจัดแนวบรรทัด อ่านอย่างเดียว [LineAlignment](../linealignment/). |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_BeginArrowheadLength](./get_beginarrowheadlength/)() | คืนค่าความยาวหัวลูกศรที่จุดเริ่มต้นของบรรทัด อ่านอย่างเดียว [LineArrowheadLength](../linearrowheadlength/). |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_BeginArrowheadStyle](./get_beginarrowheadstyle/)() | คืนรูปแบบหัวลูกศรที่จุดเริ่มต้นของบรรทัด อ่านอย่างเดียว [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_BeginArrowheadWidth](./get_beginarrowheadwidth/)() | คืนค่าความกว้างหัวลูกศรที่จุดเริ่มต้นของบรรทัด อ่านอย่างเดียว [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual [LineCapStyle](../linecapstyle/) [get_CapStyle](./get_capstyle/)() | คืนค่ารูปแบบปิดท้ายบรรทัด อ่านอย่างเดียว [LineCapStyle](../linecapstyle/). |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**float**\> [get_CustomDashPattern](./get_customdashpattern/)() | คืนรูปแบบ dash ที่กำหนดเอง อ่านอย่างเดียว **float**[]. |
| virtual [LineDashStyle](../linedashstyle/) [get_DashStyle](./get_dashstyle/)() | คืนรูปแบบ dash ของบรรทัด อ่านอย่างเดียว [LineDashStyle](../linedashstyle/). |
| virtual [LineArrowheadLength](../linearrowheadlength/) [get_EndArrowheadLength](./get_endarrowheadlength/)() | คืนค่าความยาวหัวลูกศรที่ท้ายบรรทัด อ่านอย่างเดียว [LineArrowheadLength](../linearrowheadlength/). |
| virtual [LineArrowheadStyle](../linearrowheadstyle/) [get_EndArrowheadStyle](./get_endarrowheadstyle/)() | คืนรูปแบบหัวลูกศรที่ท้ายบรรทัด อ่านอย่างเดียว [LineArrowheadStyle](../linearrowheadstyle/). |
| virtual [LineArrowheadWidth](../linearrowheadwidth/) [get_EndArrowheadWidth](./get_endarrowheadwidth/)() | คืนค่าความกว้างหัวลูกศรที่ท้ายบรรทัด อ่านอย่างเดียว [LineArrowheadWidth](../linearrowheadwidth/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFillFormatEffectiveData](../ilinefillformateffectivedata/)\> [get_FillFormat](./get_fillformat/)() | คืนรูปแบบการเติมของบรรทัด อ่านอย่างเดียว [ILineFillFormatEffectiveData](../ilinefillformateffectivedata/). |
| virtual [LineJoinStyle](../linejoinstyle/) [get_JoinStyle](./get_joinstyle/)() | คืนรูปแบบการต่อบรรทัด อ่านอย่างเดียว [LineJoinStyle](../linejoinstyle/). |
| virtual **float** [get_MiterLimit](./get_miterlimit/)() | คืนค่าขีดจำกัดมิตเตอร์ของบรรทัด อ่านอย่างเดียว **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISketchFormatEffectiveData](../isketchformateffectivedata/)\> [get_SketchFormat](./get_sketchformat/)() | คืนรูปแบบสเก็ตช์ของบรรทัด อ่านอย่างเดียว [ISketchFormatEffectiveData](../isketchformateffectivedata/). |
| virtual [LineStyle](../linestyle/) [get_Style](./get_style/)() | คืนรูปแบบบรรทัด อ่านอย่างเดียว [LineStyle](../linestyle/). |
| virtual **double** [get_Width](./get_width/)() | คืนความกว้างของบรรทัด อ่านอย่างเดียว **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อเนกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจกต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของอ็อบเจกต์ อเนกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่ targetType ระบุหรือไม่ อเนกของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เหมือนคำสั่ง lock() ของ C# เพื่อล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อเนกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถคล cloning ประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบโดยอ้างอิงวัตถุประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงร่วมโดยค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อเนกของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เหมือนการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เหมือนการปลดล็อกของคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับ weak reference ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวน weak reference ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## หมายเหตุ

อินเทอร์เฟซนี้ใช้ร่วมกับอินเทอร์เฟซ [ILineFormat](../ilineformat/) เพื่อคืนค่าการจัดรูปแบบที่มีผลโดยมีการใช้การสืบทอด

## ดูเพิ่มเติม

* คลาส [ILineParamSource](../ilineparamsource/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)