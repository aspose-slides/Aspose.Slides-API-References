---
title: ICell
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เป็นตัวแทนของเซลล์ในตาราง.
type: docs
weight: 1639
url: /th/aspose.slides/icell/
---
## ICell คลาส

เป็นตัวแทนของเซลล์ในตาราง.

```cpp
class ICell : public Aspose::Slides::ISlideComponent
```

## Methods

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น. |
| virtual **bool** [get_AnchorCenter](./get_anchorcenter/)() | กำหนดว่ากล่องข้อความอยู่กึ่งกลางภายในเซลล์หรือไม่ อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() | คืนค่าอ็อบเจ็กต์ [CellFormat](../cellformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบสำหรับเซลล์นี้ อ่านอย่างเดียว [ICellFormat](../icellformat/). |
| virtual **int32_t** [get_ColSpan](./get_colspan/)() | คืนค่าจำนวนคอลัมน์ของกริดในตารางแม่ที่เซลล์ปัจจุบันจะครอบคลุมคุณสมบัตินี้ทำให้เซลล์ดูเหมือนว่าถูกผสาน เนื่องจากครอบขอบแนวตั้งของเซลล์อื่นในตาราง อ่านอย่างเดียว **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() | รับคอลัมน์แรกของเซลล์ อ่านอย่างเดียว [IColumn](../icolumn/). |
| virtual **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() | คืนค่าดัชนีของคอลัมน์แรกที่เซลล์ครอบคลุม อ่านอย่างเดียว **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() | รับแถวแรกของเซลล์ อ่านอย่างเดียว [IRow](../irow/). |
| virtual **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() | คืนค่าดัชนีของแถวแรกที่เซลล์ครอบคลุม อ่านอย่างเดียว **int32_t**. |
| virtual **double** [get_Height](./get_height/)() | คืนค่าความสูงของเซลล์ อ่านอย่างเดียว **double**. |
| virtual **bool** [get_IsMergedCell](./get_ismergedcell/)() | คืนค่า true หากเซลล์ถูกผสานกับเซลล์ที่ปรับแล้ว มิฉะนั้นคืนค่า false อ่านอย่างเดียว **bool**. |
| virtual **double** [get_MarginBottom](./get_marginbottom/)() | คืนค่าขอบล่างใน [TextFrame](../textframe/) อ่าน **double**. |
| virtual **double** [get_MarginLeft](./get_marginleft/)() | คืนค่าขอบซ้ายใน [TextFrame](../textframe/) อ่าน **double**. |
| virtual **double** [get_MarginRight](./get_marginright/)() | คืนค่าขอบขวาใน [TextFrame](../textframe/) อ่าน **double**. |
| virtual **double** [get_MarginTop](./get_margintop/)() | คืนค่าขอบบนใน [TextFrame](../textframe/) อ่าน **double**. |
| virtual **double** [get_MinimalHeight](./get_minimalheight/)() | คืนค่าความสูงต่ำสุดของเซลล์ ซึ่งเป็นผลรวมของความสูงขั้นต่ำของทุกแถวที่เซลล์ครอบคลุม อ่านอย่างเดียว **double**. |
| virtual **double** [get_OffsetX](./get_offsetx/)() | คืนค่าระยะจากด้านซ้ายของตารางถึงด้านซ้ายของเซลล์ อ่านอย่างเดียว **double**. |
| virtual **double** [get_OffsetY](./get_offsety/)() | คืนค่าระยะจากด้านบนของตารางถึงด้านบนของเซลล์ อ่านอย่างเดียว **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | คืนค่าการนำเสนอ อ่านอย่างเดียว [IPresentation](../ipresentation/). |
| virtual **int32_t** [get_RowSpan](./get_rowspan/)() | คืนค่าจำนวนแถวที่เซลล์ที่ผสานครอบคลุม ใช้ร่วมกับแอตทริบิวต์ vMerge บนเซลล์อื่นเพื่อระบุเซลล์เริ่มต้นของการผสานแนวนอน อ่านอย่างเดียว **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | คืนค่าสไลด์ฐาน อ่านอย่างเดียว [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() | คืนค่าอ็อบเจ็กต์ [Table](../table/) พ่อแม่สำหรับเซลล์ อ่านอย่างเดียว [ITable](../itable/). |
| virtual [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() | คืนค่าชนิดของตำแหน่งยึดข้อความ อ่าน [Slides::TextAnchorType](../textanchortype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() | คืนค่าเฟรมข้อความของเซลล์ อ่านอย่างเดียว [ITextFrame](../itextframe/). |
| virtual [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() | คืนค่าชนิดของข้อความแนวตั้ง อ่าน [Slides::TextVerticalType](../textverticaltype/). |
| virtual **double** [get_Width](./get_width/)() | คืนค่าความกว้างของเซลล์ อ่านอย่างเดียว **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | ฟังก์ชันคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ ฟังก์ชันคล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่ระบุโดย targetType หรือไม่ ฟังก์ชันคล้ายกับออปเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เชิงล็อกของคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ฟังก์ชันคล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์แบบค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่ใช้ร่วมกันตามค่าที่ระบุ. |
| virtual void [set_AnchorCenter](./set_anchorcenter/)(**bool**) | กำหนดว่ากล่องข้อความอยู่กึ่งกลางภายในเซลล์หรือไม่ เขียน **bool**. |
| virtual void [set_MarginBottom](./set_marginbottom/)(**double**) | ตั้งค่าขอบล่างใน [TextFrame](../textframe/) เขียน **double**. |
| virtual void [set_MarginLeft](./set_marginleft/)(**double**) | ตั้งค่าขอบซ้ายใน [TextFrame](../textframe/) เขียน **double**. |
| virtual void [set_MarginRight](./set_marginright/)(**double**) | ตั้งค่าขอบขวาใน [TextFrame](../textframe/) เขียน **double**. |
| virtual void [set_MarginTop](./set_margintop/)(**double**) | ตั้งค่าขอบบนใน [TextFrame](../textframe/) เขียน **double**. |
| virtual void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) | ตั้งค่าชนิดตำแหน่งยึดข้อความ เขียน [Slides::TextAnchorType](../textanchortype/). |
| virtual void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) | ตั้งค่าชนิดของข้อความแนวตั้ง เขียน [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; แทนที่ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่ใช้ร่วมกันและคืนค่า ไม่ควรเรียกโดยตรง; แทนที่ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual void [SplitByColSpan](./splitbycolspan/)(**int32_t**) | แยกเซลล์เป็นสองเซลล์ตามดัชนีของคอลัมน์. |
| virtual void [SplitByHeight](./splitbyheight/)(**double**) | แยกเซลล์ตามความสูง. |
| virtual void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) | แยกเซลล์เป็นสองเซลล์ตามดัชนีของแถว. |
| virtual void [SplitByWidth](./splitbywidth/)(**double**) | แยกเซลล์ตามความกว้าง. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ฟังก์ชันคล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่สร้างโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกของคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนที่ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนที่ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## See Also

* คลาส [ISlideComponent](../islidecomponent/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)