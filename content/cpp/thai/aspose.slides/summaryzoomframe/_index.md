---
title: SummaryZoomFrame
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เป็นวัตถุ Summary Zoom ในสไลด์
type: docs
weight: 5318
url: /th/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame คลาส


Represents a Summary Zoom object in a slide.

```cpp
class SummaryZoomFrame : public Aspose::Slides::GraphicalObject,
                         public Aspose::Slides::ISummaryZoomFrame
```

## Methods

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | เพิ่มตัวแสดงตำแหน่งใหม่หากไม่มีและตั้งค่าคุณสมบัติตัวแสดงตำแหน่งให้เป็นค่าที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงตามสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าโดยใช้สไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating-point สไตล์ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating-point สไตล์ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ว่าตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | คืนค่าข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | คืนค่าชื่อเรื่องของข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง อ่าน [System::String](../../system/string/) |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | คุณสมบัติกำหนดว่ารูปร่างจะถูกแสดงผลในโหมดสีขาว-ดำอย่างไร อ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | คืนค่าข้อมูลกำหนดเองของรูปร่าง อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | คืนค่าอ็อบเจ็กต์ [EffectFormat](../effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์ อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | คืนค่าอ็อบเจ็กต์ [FillFormat](../fillformat/) ที่มีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติมสี อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | คืนคุณสมบัติของกรอบรูปร่าง อ่าน [IShapeFrame](../ishapeframe/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | คืนค่าการล็อกของรูปร่าง อ่านอย่างเดียว [IGraphicalObjectLock](../igraphicalobjectlock/) |
| **float** [get_Height](../shape/get_height/)() override | รับความสูงของรูปร่างเป็นจุด อ่าน **float** |
| **bool** [get_Hidden](../shape/get_hidden/)() override | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ อ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | คืนค่าลิงก์ที่กำหนดสำหรับคลิกเมาส์ อ่าน [IHyperlink](../ihyperlink/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | คืนค่าตัวจัดการลิงก์ อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | คืนค่าลิงก์ที่กำหนดสำหรับเมาส์โอเวอร์ อ่าน [IHyperlink](../ihyperlink/) |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | กำหนดว่ารูปร่างถูกจัดกลุ่มหรือไม่ อ่านอย่างเดียว **bool** |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว **bool** |
| [ZoomLayout](../zoomlayout/) [get_Layout](./get_layout/)() override | รับการจัดเรียงของส่วน Summary Zoom ในกรอบ ค่าเริ่มต้นคือ GridLayout |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | คืนค่าอ็อบเจ็กต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเส้น อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | คืนชื่อของรูปร่าง ต้องไม่เป็นค่า null หากต้องการใช้ค่าว่างให้ใช้สตริงว่าง อ่าน [System::String](../../system/string/) |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | คืนค่าตัวระบุที่เป็นเอกลักษณ์ระดับสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้อย่างมั่นใจจากทุกตำแหน่งในเอกสาร อ่านอย่างเดียว **uint32_t** ดูเพิ่มเติม [Shape::get_UniqueId](../shape/get_uniqueid/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | คืนอ็อบเจ็กต์แม่ [GroupShape](../groupshape/) หากรูปร่างถูกจัดกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | คืนตัวแสดงตำแหน่งสำหรับรูปร่าง คืนค่า null หากรูปร่างไม่มีตัวแสดงตำแหน่ง อ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | คืนการนำเสนอแม่ของสไลด์ อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | คืนคุณสมบัติกรอบรูปร่างดิบ อ่าน [IShapeFrame](../ishapeframe/) |
| **float** [get_Rotation](../shape/get_rotation/)() override | คืนค่ามุมการหมุนของรูปร่างที่ระบุรอบแกน z เป็นหน่วยองศา ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา อ่าน **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | คืนค่าการล็อกของรูปร่าง อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | คืนสไลด์แม่ของรูปร่าง อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomSectionCollection](../isummaryzoomsectioncollection/)\> [get_SummaryZoomCollection](./get_summaryzoomcollection/)() override | รับ [ISummaryZoomSectionCollection](../isummaryzoomsectioncollection/) สำหรับอ็อบเจ็กต์ Summary Zoom Frame |
| [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomSection](../isummaryzoomsection/)\> [get_SummaryZoomSection](./get_summaryzoomsection/)(**int32_t**) override | คืนค่าอ็อบเจ็กต์ Summary Zoom [Section](../section/) ในสไลด์ตามดัชนีที่ระบุ อ่านอย่างเดียว [Aspose::Slides::ISummaryZoomSection](../isummaryzoomsection/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | คืนค่าอ็อบเจ็กต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | คืนตัวระบุภายในระดับการนำเสนอที่ออกแบบให้ใช้โดย add-in หรือโค้ดอื่น เนื่องจากค่านี้อาจถูกกำหนดค่าใหม่โดยผู้ใช้หรือโปรแกรม ควรไม่ถือว่าเป็นคีย์ที่คงที่และเป็นเอกลักษณ์ อ่านอย่างเดียว **uint32_t** ดูเพิ่มเติม [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/) |
| **float** [get_Width](../shape/get_width/)() override | รับความกว้างของรูปร่างเป็นจุด อ่าน **float** |
| **float** [get_X](../shape/get_x/)() override | รับพิกัด x ของมุมบนซ้ายของรูปร่างเป็นจุด อ่าน **float** |
| **float** [get_Y](../shape/get_y/)() override | รับพิกัด y ของมุมบนซ้ายของรูปร่างเป็นจุด อ่าน **float** |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | คืนตำแหน่งของรูปร่างในลำดับ z Shapes[0] คืนรูปร่างที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าของลำดับ z อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | คืนรูปร่างตัวแสดงตำแหน่งพื้นฐาน (รูปร่างจากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอดมา) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อานาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชวัตถุที่กำหนดเองได้ |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | คืนรูปย่อนของรูปร่าง [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ชนิดขอบเขตรูปย่อนของรูปร่างจะใช้เป็นค่าเริ่มต้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | คืนรูปย่อนของรูปร่าง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ อานาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ อานาล็อกของตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เป็นการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อานาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถคล cloning ประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างวัตถุ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และเปิดให้สร้างสำเนาของซับคลาสได้ |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และเปิดให้สร้างสำเนาของซับคลาสได้ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การแยกประเภทของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การแยกประเภทของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | กำหนดว่ารูปร่างนี้ไม่ใช่ตัวแสดงตำแหน่ง |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | ตั้งค่าข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง เขียน [System::String](../../system/string/) |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | ตั้งชื่อเรื่องของข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง เขียน [System::String](../../system/string/) |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | คุณสมบัติกำหนดว่ารูปร่างจะถูกแสดงผลในโหมดสีขาว-ดำอย่างไร เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของกรอบรูปร่าง เขียน [IShapeFrame](../ishapeframe/) |
| void [set_Height](../shape/set_height/)(**float**) override | ตั้งค่าความสูงของรูปร่างเป็นจุด เขียน **float** |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ เขียน **bool** |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าลิงก์ที่กำหนดสำหรับคลิกเมาส์ เขียน [IHyperlink](../ihyperlink/) |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าลิงก์ที่กำหนดสำหรับเมาส์โอเวอร์ เขียน [IHyperlink](../ihyperlink/) |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | ตั้งชื่อของรูปร่าง ต้องไม่เป็น null หากต้องการใช้ค่าว่างให้ตั้งค่าสตริงว่าง เขียน [System::String](../../system/string/) |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติกรอบรูปร่างดิบ เขียน [IShapeFrame](../ishapeframe/) |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | ตั้งค่ามุมการหมุนของรูปร่างที่ระบุรอบแกน z เป็นหน่วยองศา ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา เขียน **float** |
| void [set_Width](../shape/set_width/)(**float**) override | ตั้งค่าความกว้างของรูปร่างเป็นจุด เขียน **float** |
| void [set_X](../shape/set_x/)(**float**) override | ตั้งค่าพิกัด x ของมุมบนซ้ายของรูปร่างเป็นจุด เขียน **float** |
| void [set_Y](../shape/set_y/)(**float**) override | ตั้งค่าพิกัด y ของมุมบนซ้ายของรูปร่างเป็นจุด เขียน **float** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนการเป็น shared) ช่วยให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อานาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงวัตถุที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับ weak reference ควรไม่เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับ weak reference ควรไม่เรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหา [Shape](../shape/) เป็นไฟล์ SVG |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | บันทึกเนื้อหา [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [GraphicalObject](../graphicalobject/)
* คลาส [ISummaryZoomFrame](../isummaryzoomframe/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)