---
title: ISmartArt
second_title: Aspose.Slides สำหรับ API อ้างอิงของ C++
description: แสดงไดอะแกรม SmartArt.
type: docs
weight: 1
url: /th/aspose.slides.smartart/ismartart/
---
## ISmartArt คลาส

แทนไดอะแกรม [SmartArt](../smartart/).

```cpp
class ISmartArt : public virtual Aspose::Slides::IGraphicalObject
```

## Methods

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าเฉพาะที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# โดยที่ NaN สองค่าเป็นค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนทศนิยมแบบ C# โดยที่ NaN สองค่าเป็นค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_AllNodes](./get_allnodes/)() | คืนค่าชุดของโหนดทั้งหมดในออบเจกต์ [SmartArt](../smartart/) อ่านอย่างเดียว [ISmartArtNodeCollection](../ismartartnodecollection/) |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | คืนค่าข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง อ่าน [System::String](../../system/string/) |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | คืนค่าชื่อเรื่องของข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง อ่าน [System::String](../../system/string/) |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | คุณสมบัติเชื่อมโยงวิธีที่รูปร่างจะแสดงในโหมดสีขาว-ดำ อ่าน [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) |
| virtual [SmartArtColorType](../smartartcolortype/) [get_ColorStyle](./get_colorstyle/)() | คืนค่า หรือ ตั้งค่าสไตล์สีของออบเจกต์ [SmartArt](../smartart/) อ่าน [SmartArtColorType](../smartartcolortype/) |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | คืนค่าข้อมูลกำหนดเองของรูปร่าง อ่านอย่างเดียว [ICustomData](../../aspose.slides/icustomdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | คืนค่าออบเจกต์ [EffectFormat](../../aspose.slides/effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง อ่านอย่างเดียว [IEffectFormat](../../aspose.slides/ieffectformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | คืนค่าออบเจกต์ [FillFormat](../../aspose.slides/fillformat/) ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับรูปร่าง อ่านอย่างเดียว [IFillFormat](../../aspose.slides/ifillformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | คืนค่าคุณสมบัติของกรอบรูปร่าง อ่าน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | คืนค่าการล็อกของรูปร่าง อ่านอย่างเดียว [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/) |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | รับความสูงของรูปร่าง วัดเป็นจุด อ่าน **float** |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | คืนค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการคลิกเมาส์ อ่าน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | ผู้จัดการลิงก์ไฮเปอร์ อ่านอย่างเดียว [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | คืนค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการเลื่อนเมาส์เหนือ อ่าน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | กำหนดว่ารูปร่างถูกจัดกลุ่มหรือไม่ อ่านอย่างเดียว **bool** |
| virtual **bool** [get_IsReversed](./get_isreversed/)() | คืนค่า หรือ ตั้งค่าสถานะของไดอะแกรม [SmartArt](../smartart/) เกี่ยวกับ (ซ้ายไปขวา) LTR หรือ (ขวาไปซ้าย) RTL หากไดอะแกรมรองรับการย้อนกลับ อ่าน **bool** |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | กำหนดว่ารูปร่างเป็น TextHolder หรือไม่ อ่านอย่างเดียว **bool** |
| virtual [SmartArtLayoutType](../smartartlayouttype/) [get_Layout](./get_layout/)() | คืนค่า หรือ ตั้งค่าเลย์เอาต์ของออบเจกต์ [SmartArt](../smartart/) อ่าน [SmartArtLayoutType](../smartartlayouttype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | คืนค่าออบเจกต์ [LineFormat](../../aspose.slides/lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง อ่านอย่างเดียว [ILineFormat](../../aspose.slides/ilineformat/) |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | คืนค่าชื่อของรูปร่าง อ่าน [System::String](../../system/string/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_Node](./get_node/)(**int32_t**) | คืนค่าโหนดจากชุดของโหนดรากในออบเจกต์ [SmartArt](../smartart/) ที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_NodeFromAll](./get_nodefromall/)(**int32_t**) | คืนค่าโหนดจากชุดที่มีโหนดทั้งหมดในออบเจกต์ [SmartArt](../smartart/) ที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_Nodes](./get_nodes/)() | คืนค่าชุดของโหนดรากในออบเจกต์ [SmartArt](../smartart/) อ่านอย่างเดียว [ISmartArtNodeCollection](../ismartartnodecollection/) |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | คืนค่าตัวระบุเฉพาะที่กำหนดขอบเขตสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้อย่างเชื่อถือจากใดก็ได้ในเอกสาร อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | คืนค่าออบเจกต์แม่ [GroupShape](../../aspose.slides/groupshape/) หากรูปร่างถูกจัดกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [IGroupShape](../../aspose.slides/igroupshape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | คืนค่า placeholder สำหรับรูปร่าง อ่านอย่างเดียว [IPlaceholder](../../aspose.slides/iplaceholder/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | คืนค่าสำหรับการนำเสนอ อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/) |
| virtual [SmartArtQuickStyleType](../smartartquickstyletype/) [get_QuickStyle](./get_quickstyle/)() | คืนค่า หรือ ตั้งค่าสไตล์ด่วนของออบเจกต์ [SmartArt](../smartart/) อ่าน [SmartArtQuickStyleType](../smartartquickstyletype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | คืนค่าคุณสมบัติกรอบรูปร่างดิบ อ่าน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | คืนค่ามุมองศาที่รูปร่างที่ระบุหมุนรอบแกน z ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา อ่าน **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | คืนค่าการล็อกของรูปร่าง อ่านอย่างเดียว [IBaseShapeLock](../../aspose.slides/ibaseshapelock/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | คืนค่าสไลด์ฐาน อ่านอย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | คืนค่าออบเจกต์ [ThreeDFormat](../../aspose.slides/threedformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง อ่านอย่างเดียว [IThreeDFormat](../../aspose.slides/ithreedformat/) |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | คืนค่าตัวระบุภายในที่กำหนดขอบเขตการนำเสนอซึ่งออกแบบไว้สำหรับแอด-อินหรือโค้ดอื่น ๆ เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม จึงไม่ควรถือเป็นคีย์ที่เป็นเอกลักษณ์ถาวร อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/) |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | รับความกว้างของรูปร่าง วัดเป็นจุด อ่าน **float** |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | รับพิกัด x ของมุมบนซ้ายของรูปร่าง วัดเป็นจุด อ่าน **float** |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | รับพิกัด y ของมุมบนซ้ายของรูปร่าง วัดเป็นจุด อ่าน **float** |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | คืนค่าตำแหน่งของรูปร่างในลำดับ z Shapes[0] คืนรูปร่างที่อยู่ด้านหลังของลำดับ z และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าของลำดับ z อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | คืนค่ารูป placeholder พื้นฐาน (รูปร่างจากเลย์เอาต์และ/หรือสไลด์แม่ที่รูปร่างปัจจุบันสืบทอดมา) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นการทำงานคล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการทำแฮชของออบเจกต์กำหนดเอง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | คืนค่าภาพย่อของรูปร่าง [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) ประเภทขอบเขตของภาพย่อรูปร่างใช้เป็นค่าเริ่มต้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | คืนค่าภาพย่อของรูปร่าง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจกต์ เป็นการทำงานคล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นการทำงานคล้ายออปเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentinel |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นการทำงานคล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการโคลนประเภทกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างออบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นออบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นออบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจกต์ตามการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจกต์ตามการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงของวัตถุประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเชี่ยวชาญของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเชี่ยวชาญของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายรายการ |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | ตั้งค่าข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง เขียน [System::String](../../system/string/) |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งค่าชื่อเรื่องของข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง เขียน [System::String](../../system/string/) |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | คุณสมบัติเชื่อมโยงวิธีที่รูปร่างจะแสดงในโหมดสีขาว-ดำ เขียน [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) |
| virtual void [set_ColorStyle](./set_colorstyle/)([SmartArtColorType](../smartartcolortype/)) | คืนค่า หรือ ตั้งค่าสไตล์สีของออบเจกต์ [SmartArt](../smartart/) เขียน [SmartArtColorType](../smartartcolortype/) |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | ตั้งค่าคุณสมบัติของกรอบรูปร่าง เขียน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | ตั้งค่าความสูงของรูปร่าง วัดเป็นจุด เขียน **float** |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ เขียน **bool** |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | ตั้งค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการคลิกเมาส์ เขียน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | ตั้งค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการเลื่อนเมาส์เหนือ เขียน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual void [set_IsReversed](./set_isreversed/)(**bool**) | คืนค่า หรือ ตั้งค่าสถานะของไดอะแกรม [SmartArt](../smartart/) เกี่ยวกับ (ซ้ายไปขวา) LTR หรือ (ขวาไปซ้าย) RTL หากไดอะแกรมรองรับการย้อนกลับ เขียน **bool** |
| virtual void [set_Layout](./set_layout/)([SmartArtLayoutType](../smartartlayouttype/)) | คืนค่า หรือ ตั้งค่าเลย์เอตของออบเจกต์ [SmartArt](../smartart/) เขียน [SmartArtLayoutType](../smartartlayouttype/) |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | ตั้งค่าชื่อของรูปร่าง เขียน [System::String](../../system/string/) |
| virtual void [set_QuickStyle](./set_quickstyle/)([SmartArtQuickStyleType](../smartartquickstyletype/)) | คืนค่า หรือ ตั้งค่าสไตล์ด่วนของออบเจกต์ [SmartArt](../smartart/) เขียน [SmartArtQuickStyleType](../smartartquickstyletype/) |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | ตั้งค่าคุณสมบัติของกรอบรูปร่างดิบ เขียน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | ตั้งค่ามุมองศาที่รูปร่างที่ระบุหมุนรอบแกน z ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา เขียน **float** |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | ตั้งค่าความกว้างของรูปร่าง วัดเป็นจุด เขียน **float** |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | ตั้งค่าพิกัด x ของมุมบนซ้ายของรูปร่าง วัดเป็นจุด เขียน **float** |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | ตั้งค่าพิกัด y ของมุมบนซ้ายของรูปร่าง วัดเป็นจุด เขียน **float** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า template argument ที่ n เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับ pointer ใน container ไปเป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นการทำงานคล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงออบเจกต์กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่เป็นการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentinel |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหาของ [Shape](../../aspose.slides/shape/) เป็นไฟล์ SVG |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหาของ [Shape](../../aspose.slides/shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจกต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## See Also

* คลาส [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* เนมสเปซ [Aspose::Slides::SmartArt](../)
* ไลบรารี [Aspose.Slides](../../)