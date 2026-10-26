---
title: Cell
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แสดงถึงเซลล์ของตาราง.
type: docs
weight: 300
url: /th/aspose.slides/cell/
---
## คลาส Cell

แสดงถึงเซลล์ของตาราง.

```cpp
class Cell : public Aspose::Slides::IDOMObject,
             public Aspose::Slides::ICell
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point ในสไตล์ของ C# ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point ในสไตล์ของ C# ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| **bool** [get_AnchorCenter](./get_anchorcenter/)() override | กำหนดว่ากล่องข้อความอยู่ตรงกลางภายในเซลล์หรือไม่. อ่าน **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICellFormat](../icellformat/)\> [get_CellFormat](./get_cellformat/)() override | ส่งคืนวัตถุ [CellFormat](../cellformat/) ที่มีคุณสมบัติการจัดรูปแบบสำหรับเซลล์นี้. อ่านอย่างเดียว [ICellFormat](../icellformat/). |
| **int32_t** [get_ColSpan](./get_colspan/)() override | ส่งคืนจำนวนคอลัมน์ในตารางกริดของตารางแม่ที่เซลล์ปัจจุบันจะครอบคลุม. คุณสมบัตินี้ทำให้เซลล์ดูเหมือนถูกรวมกัน เนื่องจากขยายขอบแนวตั้งของเซลล์อื่นในตาราง. อ่านอย่างเดียว **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_FirstColumn](./get_firstcolumn/)() override | รับคอลัมน์แรกของเซลล์. อ่านอย่างเดียว [IColumn](../icolumn/). |
| **int32_t** [get_FirstColumnIndex](./get_firstcolumnindex/)() override | ส่งคืนดัชนีของคอลัมน์แรกที่เซลล์ครอบคลุม. อ่านอย่างเดียว **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_FirstRow](./get_firstrow/)() override | รับแถวแรกของเซลล์. อ่านอย่างเดียว [IRow](../irow/). |
| **int32_t** [get_FirstRowIndex](./get_firstrowindex/)() override | ส่งคืนดัชนีของแถวแรกที่เซลล์ครอบคลุม. อ่านอย่างเดียว **int32_t**. |
| **double** [get_Height](./get_height/)() override | ส่งคืนความสูงของเซลล์. อ่านอย่างเดียว **double**. |
| **bool** [get_IsMergedCell](./get_ismergedcell/)() override | ส่งคืน true หากเซลล์ถูกรวมกับเซลล์ที่ปรับแล้ว, false หากไม่เป็นเช่นนั้น. อ่านอย่างเดียว **bool**. |
| **double** [get_MarginBottom](./get_marginbottom/)() override | ส่งคืนระยะขอบล่างใน [TextFrame](../textframe/). อ่าน **double**. |
| **double** [get_MarginLeft](./get_marginleft/)() override | ส่งคืนระยะขอบซ้ายใน [TextFrame](../textframe/). อ่าน **double**. |
| **double** [get_MarginRight](./get_marginright/)() override | ส่งคืนระยะขอบขวาใน [TextFrame](../textframe/). อ่าน **double**. |
| **double** [get_MarginTop](./get_margintop/)() override | ส่งคืนระยะขอบบนใน [TextFrame](../textframe/). อ่าน **double**. |
| **double** [get_MinimalHeight](./get_minimalheight/)() override | ส่งคืนความสูงขั้นต่ำของเซลล์. นี่คือผลรวมของความสูงขั้นต่ำของทุกแถวที่เซลล์ครอบคลุม. อ่านอย่างเดียว **double**. |
| **double** [get_OffsetX](./get_offsetx/)() override | ส่งคืนระยะห่างจากด้านซ้ายของตารางถึงด้านซ้ายของเซลล์. อ่านอย่างเดียว **double**. |
| **double** [get_OffsetY](./get_offsety/)() override | ส่งคืนระยะห่างจากด้านบนของตารางถึงด้านบนของเซลล์. อ่านอย่างเดียว **double**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | ส่งคืนการนำเสนอแม่ของเซลล์. อ่านอย่างเดียว [IPresentation](../ipresentation/). |
| **int32_t** [get_RowSpan](./get_rowspan/)() override | ส่งคืนจำนวนแถวที่เซลล์ที่รวมกันครอบคลุม. ใช้ร่วมกับแอตทริบิวต์ vMerge ของเซลล์อื่นเพื่อระบุเซลล์เริ่มต้นของการรวมแนวนอน. อ่านอย่างเดียว **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | ส่งคืนสไลด์แม่ของเซลล์. อ่านอย่างเดียว [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITable](../itable/)\> [get_Table](./get_table/)() override | ส่งคืนวัตถุ [Table](../table/) แม่สำหรับเซลล์. อ่านอย่างเดียว [ITable](../itable/). |
| [Aspose::Slides::TextAnchorType](../textanchortype/) [get_TextAnchorType](./get_textanchortype/)() override | ส่งคืนประเภทจุดยึดข้อความ. อ่าน [Slides::TextAnchorType](../textanchortype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | ส่งคืนกรอบข้อความของเซลล์. อ่านอย่างเดียว [ITextFrame](../itextframe/). |
| [Aspose::Slides::TextVerticalType](../textverticaltype/) [get_TextVerticalType](./get_textverticaltype/)() override | ส่งคืนประเภทของข้อความแนวตั้ง. อ่าน [Slides::TextVerticalType](../textverticaltype/). |
| **double** [get_Width](./get_width/)() override | ส่งคืนความกว้างของเซลล์. อ่านอย่างเดียว **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอานาโกลของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจกต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นอานาโกลของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอานาโกลของออปเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอานาโคลของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจกต์ใหม่และอนุญาตให้สร้างสำเนาคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจกต์ใหม่และอนุญาตให้สร้างสำเนาคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_AnchorCenter](./set_anchorcenter/)(**bool**) override | กำหนดว่ากล่องข้อความอยู่ตรงกลางภายในเซลล์หรือไม่. เขียน **bool**. |
| void [set_MarginBottom](./set_marginbottom/)(**double**) override | ตั้งค่าขอบล่างใน [TextFrame](../textframe/). เขียน **double**. |
| void [set_MarginLeft](./set_marginleft/)(**double**) override | ตั้งค่าขอบซ้ายใน [TextFrame](../textframe/). เขียน **double**. |
| void [set_MarginRight](./set_marginright/)(**double**) override | ตั้งค่าขอบขวาใน [TextFrame](../textframe/). เขียน **double**. |
| void [set_MarginTop](./set_margintop/)(**double**) override | ตั้งค่าขอบบนใน [TextFrame](../textframe/). เขียน **double**. |
| void [set_TextAnchorType](./set_textanchortype/)([Aspose::Slides::TextAnchorType](../textanchortype/)) override | ตั้งค่าประเภทจุดยึดข้อความ. เขียน [Slides::TextAnchorType](../textanchortype/). |
| void [set_TextVerticalType](./set_textverticaltype/)([Aspose::Slides::TextVerticalType](../textverticaltype/)) override | ตั้งค่าประเภทข้อความแนวตั้ง. เขียน [Slides::TextVerticalType](../textverticaltype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับการอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [SplitByColSpan](./splitbycolspan/)(**int32_t**) override | แยกเซลล์เป็นสองเซลล์โดยใช้ดัชนีของคอลัมน์. |
| void [SplitByHeight](./splitbyheight/)(**double**) override | แยกเซลล์ตามความสูง. |
| void [SplitByRowSpan](./splitbyrowspan/)(**int32_t**) override | แยกเซลล์เป็นสองเซลล์โดยใช้ดัชนีของแถว. |
| void [SplitByWidth](./splitbywidth/)(**double**) override | แยกเซลล์ตามความกว้าง. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอานาโคลของเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IDOMObject](../idomobject/)
* คลาส [ICell](../icell/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)