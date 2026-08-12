---
title: IInkActions
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แสดงวัตถุหมึกบนสไลด์.
type: docs
weight: 14
url: /th/aspose.slides.ink/iinkactions/
---
## IInkActions คลาส

Represents an ink object on a slide.

```cpp
class IInkActions : public virtual Aspose::Slides::IGraphicalObject
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | เพิ่มตัวเติมใหม่หากไม่มีและตั้งค่าคุณสมบัติตัวเติมเป็นค่าที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในรูปแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ที่ NaN สองค่าถูกพิจารณาเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | คืนข้อความสำรองที่เชื่อมโยงกับรูปทรง อ่าน [System::String](../../system/string/) |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | คืนหัวเรื่องของข้อความสำรองที่เชื่อมโยงกับรูปทรง อ่าน [System::String](../../system/string/) |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | คุณสมบัติกำหนดว่ารูปทรงจะแสดงผลในโหมดดำ-ขาวอย่างไร อ่าน [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | คืนจำนวนจุดเชื่อมต่อบนรูปทรง อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | คืนข้อมูลที่กำหนดเองของรูปทรง อ่านอย่างเดียว [ICustomData](../../aspose.slides/icustomdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | คืนอ็อบเจ็กต์ [EffectFormat](../../aspose.slides/effectformat/) ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง อ่านอย่างเดียว [IEffectFormat](../../aspose.slides/ieffectformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | คืนอ็อบเจ็กต์ [FillFormat](../../aspose.slides/fillformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบการเติมสำหรับรูปทรง อ่านอย่างเดียว [IFillFormat](../../aspose.slides/ifillformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | คืนคุณสมบัติของกรอบรูปทรง อ่าน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | คืนการล็อกของรูปทรง อ่านอย่างเดียว [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/) |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | รับค่าความสูงของรูปทรงหน่วยเป็นพอยต์ อ่าน **float** |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | กำหนดว่ารูปทรงถูกซ่อนไฟล์หรือไม่ อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | คืนไฮเปอร์ลิงก์ที่กำหนดสำหรับคลิกเม้าส์ อ่าน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | ผู้จัดการไฮเปอร์ลิงก์ อ่านอย่างเดียว [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | คืนไฮเปอร์ลิงก์ที่กำหนดสำหรับเมาส์โอเวอร์ อ่าน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | กำหนดว่ารูปทรงอยู่ในกลุ่มหรือไม่ อ่านอย่างเดียว **bool** |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | กำหนดว่ารูปทรงเป็น TextHolder หรือไม่ อ่านอย่างเดียว **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | คืนอ็อบเจ็กต์ [LineFormat](../../aspose.slides/lineformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง อ่านอย่างเดียว [ILineFormat](../../aspose.slides/ilineformat/) |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | คืนชื่อของรูปทรง อ่าน [System::String](../../system/string/) |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | คืนตัวระบุที่ไม่ซ้ำเฉพาะสไลด์ซึ่งคงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงจากที่ใดในเอกสารก็ได้ อ่านอย่างเดียว **uint32_t** ดูเพิ่มเติม [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | คืนอ็อบเจ็กต์ [GroupShape](../../aspose.slides/groupshape/) พาเรนต์หากรูปทรงอยู่ในกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [IGroupShape](../../aspose.slides/igroupshape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | คืนตัวเติมสำหรับรูปทรง อ่านอย่างเดียว [IPlaceholder](../../aspose.slides/iplaceholder/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | คืนการนำเสนอ อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | คืนคุณสมบัติของกรอบรูปทรงดิบ อ่าน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | คืนจำนวนองศาที่รูปทรงระบุถูกหมุนรอบแกน z ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา อ่าน **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | คืนการล็อกของรูปทรง 읽อย่างเดียว [IBaseShapeLock](../../aspose.slides/ibaseshapelock/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | คืนสไลด์ฐาน อ่านอย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | คืนอ็อบเจ็กต์ [ThreeDFormat](../../aspose.slides/threedformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง อ่านอย่างเดียว [IThreeDFormat](../../aspose.slides/ithreedformat/) |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | คืนตัวระบุภายในแบบสโคปของการนำเสนอซึ่งตั้งใจให้แอดอินหรือโค้ดอื่นใช้ เนื่องจากค่านี้สามารถกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรมได้ จึงไม่ควรถือว่าเป็นคีย์ที่ไม่ซ้ำถาวร อ่านอย่างเดียว **uint32_t** ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/) |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | รับความกว้างของรูปทรงหน่วยเป็นพอยต์ อ่าน **float** |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | รับพิกัด x ของมุมซ้ายบนของรูปทรงหน่วยเป็นพอยต์ อ่าน **float** |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | รับพิกัด y ของมุมซ้ายบนของรูปทรงหน่วยเป็นพอยต์ อ่าน **float** |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | คืนตำแหน่งของรูปทรงในลำดับ z Shapes[0] คืนรูปทรงที่อยู่ด้านหลังสุดของลำดับ z และ Shapes[Shapes.Count - 1] คืนรูปทรงที่อยู่ด้านหน้าสุดของลำดับ z อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | คืนรูปทรงตัวเติมพื้นฐาน (รูปทรงจากเลเอาต์และ/หรือสไลด์แม่ที่รูปทรงปัจจุบันสืบทอดมา) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อานาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ซึ่งเปิดใช้งานการทำแฮชของอ็อบเจ็กต์ที่กำหนดเอง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | คืนภาพย่อของรูปทรง [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) ประเภทขอบเขตภาพย่อของรูปทรงถูกใช้เป็นค่าเริ่มต้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | คืนภาพย่อของรูปทรง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ อานาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType อานาล็อกของโอเปอร์เรเตอร์ C# 'is' |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อานาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงอ็อบเจ็กต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | กำหนดว่ารูปทรงนี้ไม่ใช่ตัวเติม |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | ตั้งค่าข้อความสำรองที่เชื่อมโยงกับรูปทรง เขียน [System::String](../../system/string/) |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งค่าหัวเรื่องของข้อความสำรองที่เชื่อมโยงกับรูปทรง เขียน [System::String](../../system/string/) |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | คุณสมบัติกำหนดว่ารูปทรงจะแสดงผลในโหมดดำ-ขาวอย่างไร เขียน [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | ตั้งค่าคุณสมบัติของกรอบรูปทรง เขียน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | ตั้งค่าความสูงของรูปทรงหน่วยเป็นพอยต์ เขียน **float** |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | กำหนดว่ารูปทรงถูกซ่อนไฟล์หรือไม่ เขียน **bool** |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | ตั้งค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับคลิกเม้าส์ เขียน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | ตั้งค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับเมาส์โอเวอร์ เขียน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | ตั้งค่าชื่อของรูปทรง เขียน [System::String](../../system/string/) |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | ตั้งค่าคุณสมบัติของกรอบรูปทรงดิบ เขียน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | ตั้งค่าจำนวนองศาที่รูปทรงระบุถูกหมุนรอบแกน z ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา เขียน **float** |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | ตั้งค่าความกว้างของรูปทรงหน่วยเป็นพอยต์ เขียน **float** |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | ตั้งค่าพิกัด x ของมุมซ้ายบนของรูปทรงหน่วยเป็นพอยต์ เขียน **float** |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | ตั้งค่าพิกัด y ของมุมซ้ายบนของรูปทรงหน่วยเป็นพอยต์ เขียน **float** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (ไม่ใช่ shared) ซึ่งอนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อานาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) ซึ่งเปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหาของ [Shape](../../aspose.slides/shape/) เป็นไฟล์ SVG |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหาของ [Shape](../../aspose.slides/shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* เนมสเปซ [Aspose::Slides::Ink](../)
* ไลบรารี [Aspose.Slides](../../)