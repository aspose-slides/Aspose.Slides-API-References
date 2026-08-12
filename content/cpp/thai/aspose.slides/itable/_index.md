---
title: ITable
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงตารางบนสไลด์
type: docs
weight: 4018
url: /th/aspose.slides/itable/
---
## ITable คลาส

Represents a table on a slide.

```cpp
class ITable : public virtual Aspose::Slides::IGraphicalObject,
               public Aspose::Slides::IBulkTextFormattable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | เพิ่มตัวยึดตำแหน่งใหม่หากไม่มีและตั้งค่าคุณสมบัติตัวยึดตำแหน่งให้เป็นค่าที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | คืนข้อความแทนที่เชื่อมโยงกับรูปร่าง อ่าน [System::String](../../system/string/) |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | คืนหัวข้อของข้อความแทนที่เชื่อมโยงกับรูปร่าง อ่าน [System::String](../../system/string/) |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | คุณสมบัติระบุว่ารูปร่างจะถูกแสดงในโหมดสีขาว-ดำอย่างไร อ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) | คืนคอลัมน์ที่ดัชนีที่ระบุ อ่านอย่างเดียว [Aspose::Slides::IColumn](../icolumn/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() | คืนคอลเลกชันของคอลัมน์ อ่านอย่างเดียว [IColumnCollection](../icolumncollection/) |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | คืนจำนวนจุดเชื่อมต่อบนรูปร่าง อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | คืนข้อมูลกำหนดเองของรูปร่าง อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | คืนอ็อบเจกต์ [EffectFormat](../effectformat/) ซึ่งบรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | คืนอ็อบเจกต์ [FillFormat](../fillformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบการเติมสำหรับรูปร่าง อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| virtual **bool** [get_FirstCol](./get_firstcol/)() | กำหนดว่าคอลัมน์แรกของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่ อ่าน **bool** |
| virtual **bool** [get_FirstRow](./get_firstrow/)() | กำหนดว่าแถวแรกของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่ อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | คืนคุณสมบัติของเฟรมรูปร่าง อ่าน [IShapeFrame](../ishapeframe/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | คืนการล็อกของรูปร่าง อ่านอย่างเดียว [IGraphicalObjectLock](../igraphicalobjectlock/) |
| virtual **float** [get_Height](../ishape/get_height/)() | รับความสูงของรูปร่างเป็นหน่วยจุด อ่าน **float** |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ อ่าน **bool** |
| virtual **bool** [get_HorizontalBanding](./get_horizontalbanding/)() | กำหนดว่าต้องวาดแถวคู่ (even rows) ด้วยการจัดรูปแบบที่แตกต่างหรือไม่ อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | คืนลิงก์ไฮเปอร์ที่กำหนดสำหรับการคลิกเมาส์ อ่าน [IHyperlink](../ihyperlink/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ผู้จัดการลิงก์ไฮเปอร์ อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | คืนลิงก์ไฮเปอร์ที่กำหนดสำหรับการโฮเวอร์เมาส์ อ่าน [IHyperlink](../ihyperlink/) |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | กำหนดว่ารูปร่างถูกจัดกลุ่มหรือไม่ อ่านอย่างเดียว **bool** |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | กำหนดว่ารูปร่างเป็น TextHolder หรือไม่ อ่านอย่างเดียว **bool** |
| virtual **bool** [get_LastCol](./get_lastcol/)() | กำหนดว่าคอลัมน์สุดท้ายของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่ อ่าน **bool** |
| virtual **bool** [get_LastRow](./get_lastrow/)() | กำหนดว่าแถวสุดท้ายของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่ อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | คืนอ็อบเจกต์ [LineFormat](../lineformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | คืนชื่อของรูปร่าง อ่าน [System::String](../../system/string/) |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | คืนตัวระบุที่มีความเป็นเอกลักษณ์ระดับสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้อย่างน่าเชื่อถือจากทุกตำแหน่งในเอกสาร อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_UniqueId](../ishape/get_uniqueid/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | คืนอ็อบเจกต์ [GroupShape](../groupshape/) พ่อแม่หากรูปร่างถูกจัดกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | คืนตัวยึดตำแหน่งสำหรับรูปร่าง อ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | คืนงานนำเสนอ อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | คืนคุณสมบัติของเฟรมรูปร่างดิบ อ่าน [IShapeFrame](../ishapeframe/) |
| virtual **bool** [get_RightToLeft](./get_righttoleft/)() | กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่ อ่าน **bool** |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | คืนจำนวนองศาที่รูปร่างที่ระบุหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา อ่าน **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) | คืนแถวที่ดัชนีที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() | คืนคอลเลกชันของแถว อ่านอย่างเดียว [IRowCollection](../irowcollection/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | คืนการล็อกของรูปร่าง อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | คืนสไลด์ฐาน อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| virtual [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() | รับหรือกำหนดสไตล์ตารางในตัว อ่าน [TableStylePreset](../tablestylepreset/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() | คืนอ็อบเจกต์ [TableFormat](../tableformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบสำหรับตารางนี้ อ่านอย่างเดียว [ITableFormat](../itableformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | คืนอ็อบเจกต์ [ThreeDFormat](../threedformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | คืนตัวระบุภายในระดับงานนำเสนอที่ตั้งใจให้ใช้โดยแอด-อินหรือโค้ดอื่น ๆ เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรมจึงไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์แบบถาวร อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/) |
| virtual **bool** [get_VerticalBanding](./get_verticalbanding/)() | กำหนดว่าต้องวาดคอลัมน์คู่ (even columns) ด้วยการจัดรูปแบบที่แตกต่างหรือไม่ อ่าน **bool** |
| virtual **float** [get_Width](../ishape/get_width/)() | รับความกว้างของรูปร่างเป็นหน่วยจุด อ่าน **float** |
| virtual **float** [get_X](../ishape/get_x/)() | รับพิกัด x ของมุมซ้ายบนของรูปร่างเป็นหน่วยจุด อ่าน **float** |
| virtual **float** [get_Y](../ishape/get_y/)() | รับพิกัด y ของมุมซ้ายบนของรูปร่างเป็นหน่วยจุดอ่าน **float** |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | คืนตำแหน่งของรูปร่างในลำดับ z Shapes[0] คืนรูปร่างที่ท้ายสุดของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่หน้าสุดของลำดับ z อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | คืนรูปร่างตัวยึดตำแหน่งพื้นฐาน (รูปร่างจากเลเอาต์และ/หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอดมาจาก) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเวอร์ชันของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถสร้างแฮชของอ็อบเจกต์กำหนดเองได้ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | คืนรูปย่อของรูปร่าง [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ประเภทขอบเขตรูปย่อของรูปร่างจะถูกใช้เป็นค่าเริ่มต้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | คืนรูปย่อของรูปร่าง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์ เป็นเวอร์ชันของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) | คืนเซลล์ที่ตำแหน่งคอลัมน์และแถวที่ระบุ อ่านอย่างเดียว [ICell](../icell/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นเวอร์ชันของออปเรเตอร์ C# 'is' |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุเฝ้าระวัง [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเวอร์ชันของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทกำหนดเองได้ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) | รวมเซลล์ที่อยู่ข้างเคียง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรเลย จริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรเลย จริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงร่วมตามค่าที่ระบุ |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | กำหนดว่ารูปร่างนี้ไม่เป็นตัวยึดตำแหน่ง |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | ตั้งข้อความแทนที่เชื่อมโยงกับรูปร่าง เขียน [System::String](../../system/string/) |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งหัวข้อของข้อความแทนที่เชื่อมโยงกับรูปร่าง เขียน [System::String](../../system/string/) |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | คุณสมบัติระบุว่ารูปร่างจะถูกแสดงในโหมดสีขาว-ดำอย่างไร เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| virtual void [set_FirstCol](./set_firstcol/)(**bool**) | กำหนดว่าคอลัมน์แรกของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่ เขียน **bool** |
| virtual void [set_FirstRow](./set_firstrow/)(**bool**) | กำหนดว่าแถวแรกของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่ เขียน **bool** |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของเฟรมรูปร่าง เขียน [IShapeFrame](../ishapeframe/) |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ตั้งค่าความสูงของรูปร่างเป็นหน่วยจุด เขียน **float** |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ เขียน **bool** |
| virtual void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) | กำหนดว่าต้องวาดแถวคู่ด้วยการจัดรูปแบบที่แตกต่างหรือไม่ เขียน **bool** |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งลิงก์ไฮเปอร์ที่กำหนดสำหรับการคลิกเมาส์ เขียน [IHyperlink](../ihyperlink/) |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งลิงก์ไฮเปอร์ที่กำหนดสำหรับการโฮเวอร์เมาส์ เขียน [IHyperlink](../ihyperlink/) |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ตั้งตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual void [set_LastCol](./set_lastcol/)(**bool**) | กำหนดว่าคอลัมน์สุดท้ายของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่ เขียน **bool** |
| virtual void [set_LastRow](./set_lastrow/)(**bool**) | กำหนดว่าแถวสุดท้ายของตารางต้องวาดด้วยการจัดรูปแบบพิเศษหรือไม่ เขียน **bool** |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | ตั้งชื่อของรูปร่าง เขียน [System::String](../../system/string/) |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของเฟรมรูปร่างดิบ เขียน [IShapeFrame](../ishapeframe/) |
| virtual void [set_RightToLeft](./set_righttoleft/)(**bool**) | กำหนดว่าตารางมีลำดับการอ่านจากขวาไปซ้ายหรือไม่ เขียน **bool** |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | ตั้งค่าจำนวนองศาที่รูปร่างที่ระบุหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา เขียน **float** |
| virtual void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) | รับหรือกำหนดสไตล์ตารางในตัว เขียน [TableStylePreset](../tablestylepreset/) |
| virtual void [set_VerticalBanding](./set_verticalbanding/)(**bool**) | กำหนดว่าต้องวาดคอลัมน์คู่ด้วยการจัดรูปแบบที่แตกต่างหรือไม่ เขียน **bool** |
| virtual void [set_Width](../ishape/set_width/)(**float**) | ตั้งค่าความกว้างของรูปร่างเป็นหน่วยจุด เขียน **float** |
| virtual void [set_X](../ishape/set_x/)(**float**) | ตั้งค่าพิกัด x ของมุมซ้ายบนของรูปร่างเป็นหน่วยจุด เขียน **float** |
| virtual void [set_Y](../ishape/set_y/)(**float**) | ตั้งค่าพิกัด y ของมุมซ้ายบนของรูปร่างเป็นหน่วยจุด เขียน **float** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) | ตั้งค่าคุณสมบัติรูปแบบส่วนที่กำหนดให้กับส่วนทั้งหมดขององค์ประกอบ |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) | ตั้งค่าคุณสมบัติรูปแบบย่อหน้าที่กำหนดให้กับย่อหน้าทั้งหมดขององค์ประกอบ |
| virtual void [SetTextFormat](../ibulktextformattable/settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) | ตั้งค่าคุณสมบัติกรอบข้อความที่กำหนดให้กับกรอบข้อความทั้งหมดขององค์ประกอบ |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเวอร์ชันของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจกต์กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุเฝ้าระวัง [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบอ่อน ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบอ่อน ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IGraphicalObject](../igraphicalobject/)
* คลาส [IBulkTextFormattable](../ibulktextformattable/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)