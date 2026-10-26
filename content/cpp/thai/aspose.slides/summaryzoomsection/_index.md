---
title: SummaryZoomSection
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เป็นตัวแทนของอ็อบเจกต์ Summary Zoom Section ในเฟรม Summary Zoom.
type: docs
weight: 5331
url: /th/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection คลาส

แสดงถึงวัตถุ Summary Zoom [Section](../section/) ในเฟรม Summary Zoom.

```cpp
class SummaryZoomSection : public Aspose::Slides::SectionZoomFrame,
                           public Aspose::Slides::ISummaryZoomSection
```

## วิธีการ

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | เพิ่มตัวแทรกใหม่หากไม่มีและตั้งค่าคุณสมบัติตัวแทรกเป็นค่าที่ระบุ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าแบบ floating point สไตล์ C# โดยถือว่า NaN สองค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าแบบ floating point สไตล์ C# โดยถือว่า NaN สองค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | คืนค่าข้อความทางเลือกที่เชื่อมโยงกับรูปร่าง. อ่าน [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | คืนค่าชื่อเรื่องของข้อความทางเลือกที่เชื่อมโยงกับรูปร่าง. อ่าน [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | คุณสมบัติเกาะกำหนดว่ารูปร่างจะเรนเดอร์ในโหมดแสดงผลสีดำ-ขาวอย่างไร.. อ่าน [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | คืนค่าข้อมูลกำหนดเองของรูปร่าง. อ่านอย่างเดียว [ICustomData](../icustomdata/). |
| [System::String](../../system/string/) [get_Description](./get_description/)() override | คืนค่าคำอธิบายข้อความของวัตถุ Summary Zoom [Section](../section/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | คืนค่าอ็อบเจ็กต์ [EffectFormat](../effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | คืนค่าอ็อบเจ็กต์ [FillFormat](../fillformat/) ที่มีคุณสมบัติการฟอร์แมตการเติมสีสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | คืนค่าคุณสมบัติของเฟรมรูปร่าง. อ่าน [IShapeFrame](../ishapeframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | คืนค่าการล็อกของรูปร่าง. อ่านอย่างเดียว [IGraphicalObjectLock](../igraphicalobjectlock/). |
| **float** [get_Height](../shape/get_height/)() override | รับความสูงของรูปร่างหน่วยเป็นพอยต์. อ่าน **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | กำหนดว่ารูปร่างซ่อนอยู่หรือไม่. อ่าน **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | คืนค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | คืนค่าผู้จัดการลิงก์ไฮเปอร์. อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | คืนค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับเมาส์โอเวอร์. อ่าน [IHyperlink](../ihyperlink/). |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](../zoomobject/get_imagetype/)() override | รับประเภทภาพของวัตถุซูม. อ่าน [ZoomImageType](../zoomimagetype/). ค่าเริ่มต้น: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | กำหนดว่ารูปร่างรวมกลุ่มอยู่หรือไม่. อ่านอย่างเดียว **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | คืนค่าอ็อบเจ็กต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | คืนชื่อของรูปร่าง. ต้องไม่เป็น null. ใช้ค่า string ว่างหากจำเป็น. อ่าน [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | คืนค่าตัวระบุที่ไม่ซ้ำเฉพาะสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างจากที่ไหนก็ได้ในเอกสาร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | คืนอ็อบเจ็กต์พาเรนต์ [GroupShape](../groupshape/) หากรูปร่างถูกรวมกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | คืนตัวแทรกสำหรับรูปร่าง. คืนค่า null หากรูปร่างไม่มีตัวแทรก. อ่านอย่างเดียว [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | คืนการนำเสนอพาเรนต์ของสไลด์. อ่านอย่างเดียว [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | คืนคุณสมบัติของเฟรมรูปร่างดิบ. อ่าน [IShapeFrame](../ishapeframe/). |
| **bool** [get_ReturnToParent](../zoomobject/get_returntoparent/)() override | รับพฤติกรรมการนำทางในสไลด์โชว์. อ่าน **bool**. ค่าเริ่มต้น: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | คืนค่าจำนวนองศาที่รูปร่างที่กำหนดหมุนรอบแกน z. ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา. อ่าน **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | คืนค่าการล็อกของรูปร่าง. อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/). |
| **bool** [get_ShowBackground](../zoomobject/get_showbackground/)() override | รับค่าที่ระบุว่าซูมจะใช้พื้นหลังของสไลด์ปลายทางหรือไม่. อ่าน **bool**. ค่าเริ่มต้น: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | คืนสไลด์พาเรนต์ของรูปร่าง. อ่านอย่างเดียว [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](../sectionzoomframe/get_targetsection/)() override | รับอ็อบเจ็กต์ส่วนที่วัตถุ [Section](../section/) Zoom ลิงก์ไป. อ่าน [ISection](../isection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | คืนอ็อบเจ็กต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติเอฟเฟกต์ 3 มิติสำหรับรูปร่าง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติ 3d. อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/). |
| [System::String](../../system/string/) [get_Title](./get_title/)() override | คืนชื่อข้อความของวัตถุ Summary Zoom [Section](../section/). |
| **float** [get_TransitionDuration](../zoomobject/get_transitionduration/)() override | รับระยะเวลาการเปลี่ยนระหว่าง Zoom และสไลด์. อ่าน **float**. ค่าเริ่มต้น: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | คืนตัวระidentiภายในที่ระดับการนำเสนอซึ่งตั้งใจให้ใช้โดย add-ins หรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรมมิ่ง จึงไม่ควรถือว่าเป็นคีย์ที่คงที่ตลอด. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | รับความกว้างของรูปร่าง หน่วยเป็นพอยต์. อ่าน **float**. |
| **float** [get_X](../shape/get_x/)() override | รับพิกัด x ของมุมซ้ายบนของรูปร่าง หน่วยเป็นพอยต์. อ่าน **float**. |
| **float** [get_Y](../shape/get_y/)() override | รับพิกัด y ของมุมซ้ายบนของรูปร่าง หน่วยเป็นพอยต์. อ่าน **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../zoomobject/get_zoomimage/)() override | รับภาพสำหรับวัตถุซูม. อ่าน [IPPImage](../ippimage/). |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | คืนตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนรูปร่างที่อยู่ด้านหลังสุดของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าสุดของลำดับ z. อ่านอย่างเดียว **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | คืนรูปร่างตัวแทรกพื้นฐาน (รูปร่างจากเลย์เอาต์และ/หรือสไลด์หลักที่รูปร่างปัจจุบันสืบทอดจาก). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เหมือนเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของวัตถุกำหนดเอง. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | คืนภาพขนาดย่อของรูปร่าง. ประเภทขอบเขตภาพขนาดย่อของรูปร่าง [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ถูกใช้เป็นค่าเริ่มต้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | คืนภาพขนาดย่อของรูปร่าง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. เหมือนการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่ targetType ระบุหรือไม่. เหมือนตัวดำเนินการ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เหมือนเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาของประเภทกำหนดเอง. |
| [Object](../../system/object/object/)() | สร้างวัตถุ. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์มอบหมาย. จริง ๆ แล้วไม่คัดลอกอะไร เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงออบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | กำหนดว่ารูปร่างนี้ไม่ใช่ตัวแทรก. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | ตั้งค่าข้อความทางเลือกที่เชื่อมโยงกับรูปร่าง. เขียน [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | ตั้งค่าชื่อเรื่องของข้อความทางเลือกที่เชื่อมโยงกับรูปร่าง. เขียน [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | คุณสมบัติเกาะกำหนดว่ารูปร่างจะเรนเดอร์ในโหมดแสดงผลสีดำ-ขาวอย่างไร.. เขียน [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_Description](./set_description/)([System::String](../../system/string/)) override | คืนค่าคำอธิบายข้อความของวัตถุ Summary Zoom [Section](../section/). |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของเฟรมรูปร่าง. เขียน [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | ตั้งค่าความสูงของรูปร่าง หน่วยเป็นพอยต์. เขียน **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | กำหนดว่ารูปร่างซ่อนอยู่หรือไม่. เขียน **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการคลิกเมาส์. เขียน [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับเมาส์โอเวอร์. เขียน [IHyperlink](../ihyperlink/). |
| void [set_ImageType](../zoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | ตั้งค่าประเภทภาพของวัตถุซูม. เขียน [ZoomImageType](../zoomimagetype/). ค่าเริ่มต้น: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | ตั้งค่าชื่อของรูปร่าง. ต้องไม่เป็น null. ใช้ค่า string ว่างหากจำเป็น. เขียน [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของเฟรมรูปร่างดิบ. เขียน [IShapeFrame](../ishapeframe/). |
| void [set_ReturnToParent](../zoomobject/set_returntoparent/)(**bool**) override | ตั้งค่าพฤติกรรมการนำทางในสไลด์โชว์. เขียน **bool**. ค่าเริ่มต้น: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | ตั้งค่าจำนวนองศาที่รูปร่างที่กำหนดหมุนรอบแกน z. ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา. เขียน **float**. |
| void [set_ShowBackground](../zoomobject/set_showbackground/)(**bool**) override | ตั้งค่าที่ระบุว่าซูมจะใช้พื้นหลังของสไลด์ปลายทางหรือไม่. เขียน **bool**. ค่าเริ่มต้น: true |
| void [set_TargetSection](../sectionzoomframe/set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) override | ตั้งค่าอ็อบเจ็กต์ส่วนที่วัตถุ [Section](../section/) Zoom ลิงก์ไป. เขียน [ISection](../isection/). |
| void [set_Title](./set_title/)([System::String](../../system/string/)) override | คืนชื่อข้อความของวัตถุ Summary Zoom [Section](../section/). |
| void [set_TransitionDuration](../zoomobject/set_transitionduration/)(**float**) override | ตั้งค่าระยะเวลาการเปลี่ยนระหว่าง Zoom และสไลด์. เขียน **float**. ค่าเริ่มต้น: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | ตั้งค่าความกว้างของรูปร่าง หน่วยเป็นพอยต์. เขียน **float**. |
| void [set_X](../shape/set_x/)(**float**) override | ตั้งค่าพิกัด x ของมุมซ้ายบนของรูปร่าง หน่วยเป็นพอยต์. เขียน **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | ตั้งค่าพิกัด y ของมุมซ้ายบนของรูปร่าง หน่วยเป็นพอยต์. เขียน **float**. |
| void [set_ZoomImage](../zoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | ตั้งค่าภาพสำหรับวัตถุซูม. เขียน [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เหมือนเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุกำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [SectionZoomFrame](../sectionzoomframe/)
* คลาส [ISummaryZoomSection](../isummaryzoomsection/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)