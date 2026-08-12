---
title: Table
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนของตารางบนสไลด์
type: docs
weight: 5409
url: /th/aspose.slides/table/
---
## คลาส Table


Represents a table on a slide.

```cpp
class Table : public Aspose::Slides::GraphicalObject,
              public Aspose::Slides::ITable
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | เพิ่ม placeholder ใหม่ถ้าไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ชนิดอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ชนิดค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | ส่งกลับข้อความแทนที่เชื่อมโยงกับรูปทรง อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | ส่งกลับหัวข้อของข้อความแทนที่เชื่อมโยงกับรูปทรง อ่าน [System::String](../../system/string/) |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | คุณสมบัติกำหนดรูปแบบการแสดงผลของรูปทรงในโหมดสีขาว-ดำอ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumn](../icolumn/)\> [get_Column](./get_column/)(**int32_t**) override | ส่งกลับคอลัมน์ที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [Aspose::Slides::IColumn](../icolumn/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColumnCollection](../icolumncollection/)\> [get_Columns](./get_columns/)() override | ส่งกลับคอลเลกชันของคอลัมน์ อ่านอย่างเดียว [IColumnCollection](../icolumncollection/) |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | ส่งกลับจำนวนจุดเชื่อมต่อบนรูปทรง อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | ส่งกลับข้อมูลกำหนดเองของรูปทรง อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | ส่งกลับอ็อบเจ็กต์ [EffectFormat](../effectformat/) ซึ่งประกอบด้วยเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์ อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | ส่งกลับอ็อบเจ็กต์ [TableFormat::get_FillFormat](../tableformat/get_fillformat/) ที่มีการฟอร์แมตการเติมสำหรับ [Table](./) อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| **bool** [get_FirstCol](./get_firstcol/)() override | กำหนดว่าคอลัมน์แรกของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ อ่าน **bool** |
| **bool** [get_FirstRow](./get_firstrow/)() override | กำหนดว่าแถวแรกของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ อ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | ส่งกลับคุณสมบัติของเฟรมรูปทรง อ่าน [IShapeFrame](../ishapeframe/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | ส่งกลับการล็อกของรูปทรง อ่านอย่างเดียว [IGraphicalObjectLock](../igraphicalobjectlock/) |
| **float** [get_Height](../shape/get_height/)() override | รับความสูงของรูปทรงหน่วยเป็นพ้อยท์ อ่าน **float** |
| **bool** [get_Hidden](../shape/get_hidden/)() override | กำหนดว่ารูปทรงถูกซ่อนไหม อ่าน **bool** |
| **bool** [get_HorizontalBanding](./get_horizontalbanding/)() override | กำหนดว่าบรรทัดคู่ต้องวาดด้วยรูปแบบที่ต่างกันหรือไม่ อ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | ส่งกลับไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์ อ่าน [IHyperlink](../ihyperlink/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | ส่งกลับตัวจัดการไฮเปอร์ลิงก์ อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | ส่งกลับไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ อ่าน [IHyperlink](../ihyperlink/) |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | กำหนดว่ารูปทรงเป็นการกลุ่มหรือไม่ อ่านอย่างเดียว **bool** |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว **bool** |
| **bool** [get_LastCol](./get_lastcol/)() override | กำหนดว่าคอลัมน์สุดท้ายของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ อ่าน **bool** |
| **bool** [get_LastRow](./get_lastrow/)() override | กำหนดว่าแถวสุดท้ายของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ อ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | ส่งกลับอ็อบเจ็กต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติการฟอร์แมตเส้นสำหรับรูปทรง หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเส้น อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | ส่งกลับชื่อของรูปทรง ต้องไม่เป็น null หากต้องการให้ใช้สตริงว่าง อ่าน [System::String](../../system/string/) |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | ส่งกลับตัวระบุที่ไม่ซ้ำกันระดับสไลด์ซึ่งคงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงจากทุกที่ในเอกสารได้อย่างน่าเชื่อถือ อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_UniqueId](../shape/get_uniqueid/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | ส่งกลับอ็อบเจ็กต์ [GroupShape](../groupshape/) พาเรนท์หากรูปทรงถูกกลุ่ม มิฉะนั้นส่งคืน null อ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | ส่งกลับ placeholder สำหรับรูปทรง ส่งคืน null หากรูปทรงไม่มี placeholder อ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | ส่งกลับพาเรนท์พรีเซนเทชันของสไลด์ อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | ส่งกลับคุณสมบัติของเฟรมรูปทรงดิบ อ่าน [IShapeFrame](../ishapeframe/) |
| **bool** [get_RightToLeft](./get_righttoleft/)() override | กำหนดว่าตารางมีการอ่านจากขวาไปซ้ายหรือไม่ อ่าน **bool** |
| **float** [get_Rotation](../shape/get_rotation/)() override | ส่งกลับจำนวนองศาที่รูปทรงกำหนดถูกหมุนรอบแกน z ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา อ่าน **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IRow](../irow/)\> [get_Row](./get_row/)(**int32_t**) override | ส่งกลับแถวที่ตำแหน่งที่ระบุ |
| [System::SharedPtr](../../system/sharedptr/)\<[IRowCollection](../irowcollection/)\> [get_Rows](./get_rows/)() override | ส่งกลับคอลเลกชันของแถว อ่านอย่างเดียว [IRowCollection](../irowcollection/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | ส่งกลับการล็อกของรูปทรง อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | ส่งกลับสไลด์พาเรนท์ของรูปทรง อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| [TableStylePreset](../tablestylepreset/) [get_StylePreset](./get_stylepreset/)() override | รับสไตล์ตาราง builtin อ่าน [TableStylePreset](../tablestylepreset/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITableFormat](../itableformat/)\> [get_TableFormat](./get_tableformat/)() override | ส่งกลับอ็อบเจ็กต์ [TableFormat](../tableformat/) ที่มีคุณสมบัติการฟอร์แมตสำหรับตารางนี้ อ่านอย่างเดียว [ITableFormat](../itableformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | ส่งกลับอ็อบเจ็กต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปทรง หมายเหตุ: อาจคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3 มิติอ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | ส่งกลับตัวระบุภายในระดับพรีเซนเทชันที่ใช้สำหรับแอดอินหรือโค้ดอื่น ๆ เนื่องจากค่านี้สามารถกำหนดใหม่โดยผู้ใช้หรือโปรแกรมได้ จึงไม่ควรถือว่าเป็นคีย์ที่คงที่ อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/) |
| **bool** [get_VerticalBanding](./get_verticalbanding/)() override | กำหนดว่าคอลัมน์คู่ต้องวาดด้วยรูปแบบที่ต่างกันหรือไม่ อ่าน **bool** |
| **float** [get_Width](../shape/get_width/)() override | รับความกว้างของรูปทรงหน่วยเป็นพ้อยท์ อ่าน **float** |
| **float** [get_X](../shape/get_x/)() override | รับค่า x-coordinate ของมุมซ้ายบนของรูปทรงหน่วยเป็นพ้อยท์ อ่าน **float** |
| **float** [get_Y](../shape/get_y/)() override | รับค่า y-coordinate ของมุมซ้ายบนของรูปทรงหน่วยเป็นพ้อยท์ อ่าน **float** |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | ส่งกลับตำแหน่งของรูปทรงในลำดับ z Shapes[0] ส่งกลับรูปทรงที่อยู่ด้านหลังสุดของลำดับ z และ Shapes[Shapes.Count - 1] ส่งกลับรูปทรงที่อยู่ด้านหน้าสุดของลำดับ z อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | ส่งกลับรูป placeholder พื้นฐาน (รูปจากเลเอาต์และ/หรือมาสเตอร์สไลด์ที่รูปปัจจุบันสืบทอดมาจาก) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับออบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชออบเจ็กต์กำหนดเองได้ |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | ส่งกลับรูปลูกศรของรูปทรง [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ชนิดขอบเขตรูปลูกศรของรูปทรงใช้เป็นค่าเริ่มต้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | ส่งกลับรูปลูกศรของรูปทรง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์ อนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่แสดงผล |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [idx_get](./idx_get/)(**int32_t**, **int32_t**) override | ส่งกลับเซลล์ที่ตำแหน่งคอลัมน์และแถวที่ระบุ อ่านอย่างเดียว [Cell](../cell/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่ targetType อธิบายไหม อนาล็อกของออปเรเตอร์ C# 'is' |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ lock() ของ C# เพื่อทำการล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทกำหนดเองได้ |
| [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\> [MergeCells](./mergecells/)([System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, [System::SharedPtr](../../system/sharedptr/)\<[ICell](../icell/)\>, **bool**) override | รวมเซลล์ที่อยู่เคียงกัน |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นออบเจ็กต์ใหม่และอนุญาตให้สร้างสำเนาสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ออปเรเตอร์การมอบหมาย ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นออบเจ็กต์ใหม่และอนุญาตให้สร้างสำเนาสำหรับคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | อ้างอิงเปรียบเทียบออบเจ็กต์ชนิดค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | ตั้งข้อความแทนที่เชื่อมโยงกับรูปทรง เขียน [System::String](../../system/string/) |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | ตั้งหัวข้อของข้อความแทนที่เชื่อมโยงกับรูปทรง เขียน [System::String](../../system/string/) |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | คุณสมบัติกำหนดรูปแบบการแสดงผลของรูปทรงในโหมดสีขาว-ดำ เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| void [set_FirstCol](./set_firstcol/)(**bool**) override | กำหนดว่าคอลัมน์แรกของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ เขียน **bool** |
| void [set_FirstRow](./set_firstrow/)(**bool**) override | กำหนดว่าแถวแรกของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ เขียน **bool** |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของเฟรมรูปทรง เขียน [IShapeFrame](../ishapeframe/) |
| void [set_Height](../shape/set_height/)(**float**) override | ตั้งค่าความสูงของรูปทรงหน่วยเป็นพ้อยท์ เขียน **float** |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | ตั้งค่าว่ารูปทรงถูกซ่อนหรือไม่ เขียน **bool** |
| void [set_HorizontalBanding](./set_horizontalbanding/)(**bool**) override | ตั้งค่าว่าบรรทัดคู่ต้องวาดด้วยรูปแบบที่ต่างกันหรือไม่ เขียน **bool** |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์ เขียน [IHyperlink](../ihyperlink/) |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ เขียน [IHyperlink](../ihyperlink/) |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| void [set_LastCol](./set_lastcol/)(**bool**) override | กำหนดว่าคอลัมน์สุดท้ายของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ เขียน **bool** |
| void [set_LastRow](./set_lastrow/)(**bool**) override | กำหนดว่าแถวสุดท้ายของตารางต้องวาดด้วยรูปแบบพิเศษหรือไม่ เขียน **bool** |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | ตั้งชื่อของรูปทรง ต้องไม่เป็น null หากต้องการให้ใช้สตริงว่าง เขียน [System::String](../../system/string/) |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของเฟรมรูปทรงดิบ เขียน [IShapeFrame](../ishapeframe/) |
| void [set_RightToLeft](./set_righttoleft/)(**bool**) override | กำหนดว่าตารางมีการอ่านจากขวาไปซ้ายหรือไม่ เขียน **bool** |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | ตั้งค่าจำนวนองศาที่รูปทรงกำหนดถูกหมุนรอบแกน z ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา เขียน **float** |
| void [set_StylePreset](./set_stylepreset/)([TableStylePreset](../tablestylepreset/)) override | ตั้งค่าสไตล์ตาราง builtin เขียน [TableStylePreset](../tablestylepreset/) |
| void [set_VerticalBanding](./set_verticalbanding/)(**bool**) override | กำหนดว่าคอลัมน์คู่ต้องวาดด้วยรูปแบบที่ต่างกันหรือไม่ เขียน **bool** |
| void [set_Width](../shape/set_width/)(**float**) override | ตั้งค่าความกว้างของรูปทรงหน่วยเป็นพ้อยท์ เขียน **float** |
| void [set_X](../shape/set_x/)(**float**) override | ตั้งค่า x-coordinate ของมุมซ้ายบนของรูปทรงหน่วยเป็นพ้อยท์ เขียน **float** |
| void [set_Y](../shape/set_y/)(**float**) override | ตั้งค่า y-coordinate ของมุมซ้ายบนของรูปทรงหน่วยเป็นพ้อยท์ เขียน **float** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า template argument ที่ n ให้เป็น weak pointer (แทนที่ shared) อนุญาตให้เปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\>) override | ตั้งค่าคุณสมบัติรูปแบบส่วนที่กำหนดให้กับทุกส่วนของเซลล์ตาราง |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormat](../iparagraphformat/)\>) override | ตั้งค่าคุณสมบัติรูปแบบย่อหน้าที่กำหนดให้กับย่อหน้าทั้งหมดของเซลล์ตาราง |
| void [SetTextFormat](./settextformat/)([System::SharedPtr](../../system/sharedptr/)\<[ITextFrameFormat](../itextframeformat/)\>) override | ตั้งค่าคุณสมบัติรูปแบบเฟรมข้อความที่กำหนดให้กับเฟรมข้อความทั้งหมดของเซลล์ตาราง |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และส่งคืน ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงออบเจ็กต์กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อก lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [GraphicalObject](../graphicalobject/)
* คลาส [ITable](../itable/)
* เนมสเปส [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)