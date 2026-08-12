---
title: IZoomObject
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงวัตถุ Zoom ในสไลด์.
type: docs
weight: 4265
url: /th/aspose.slides/izoomobject/
---
## IZoomObject คลาส


แสดงวัตถุ Zoom ในสไลด์.

```cpp
class IZoomObject : public virtual Aspose::Slides::IGraphicalObject
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้เป็นค่าที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบอ้างอิงตามสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุแบบค่า (value type) ตามสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# ที่ NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# ที่ NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | คืนค่าข้อความแทนที่ที่เชื่อมโยงกับรูปทรง อ่าน [System::String](../../system/string/) |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | คืนค่าชื่อของข้อความแทนที่ที่เชื่อมโยงกับรูปทรง อ่าน [System::String](../../system/string/) |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | คุณสมบัติกำหนดว่ารูปทรงจะแสดงอย่างไรในโหมดสีขาว-ดำ อ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | คืนค่าจำนวนจุดเชื่อมต่อบนรูปทรง อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | คืนค่าข้อมูลกำหนดเองของรูปทรง อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | คืนค่าอ็อบเจกต์ [EffectFormat](../effectformat/) ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | คืนค่าอ็อบเจกต์ [FillFormat](../fillformat/) ที่บรรจุตามคุณสมบัติการจัดรูปแบบการเติมสำหรับรูปทรง อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | คืนค่าคุณสมบัติของเฟรมรูปทรง อ่าน [IShapeFrame](../ishapeframe/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | คืนค่าการล็อกของรูปทรง อ่านอย่างเดียว [IGraphicalObjectLock](../igraphicalobjectlock/) |
| virtual **float** [get_Height](../ishape/get_height/)() | ดึงความสูงของรูปทรงที่วัดเป็นจุด อ่าน **float** |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | กำหนดว่ารูปทรงซ่อนอยู่หรือไม่ อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | คืนค่า hyperlink ที่กำหนดสำหรับการคลิกเมาส์ อ่าน [IHyperlink](../ihyperlink/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ตัวจัดการ Hyperlink อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | คืนค่า hyperlink ที่กำหนดสำหรับเมาส์อยู่เหนือ อ่าน [IHyperlink](../ihyperlink/) |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](./get_imagetype/)() | ดึงประเภทภาพของวัตถุ zoom อ่าน [ZoomImageType](../zoomimagetype/) ค่าเริ่มต้น: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | ดึงตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | กำหนดว่ารูปทรงอยู่ในกลุ่มหรือไม่ อ่านอย่างเดียว **bool** |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | กำหนดว่ารูปทรงเป็น TextHolder หรือไม่ อ่านอย่างเดียว **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | คืนค่าอ็อบเจกต์ [LineFormat](../lineformat/) ที่บรรจุตามคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | คืนชื่อของรูปทรง อ่าน [System::String](../../system/string/) |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | คืนค่า identifier ที่ไม่ซ้ำเฉพาะสไลด์ซึ่งคงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงได้อย่างน่าเชื่อถือจากทุกที่ในเอกสาร อ่านอย่างเดียว **uint32_t** ดูเพิ่มเติม [IShape::get_UniqueId](../ishape/get_uniqueid/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | คืนค่าอ็อบเจกต์แม่ [GroupShape](../groupshape/) หากรูปทรงอยู่ในกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | คืนค่า placeholder ของรูปทรง อ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | คืนค่าการนำเสนอ อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | คืนค่าคุณสมบัติของเฟรมรูปทรงดิบ อ่าน [IShapeFrame](../ishapeframe/) |
| virtual **bool** [get_ReturnToParent](./get_returntoparent/)() | ดึงพฤติกรรมการนำทางในสไลด์โชว์ อ่าน **bool** ค่าเริ่มต้น: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | คืนค่าจำนวนองศาที่รูปทรงระบุหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา อ่าน **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | คืนค่าการล็อกของรูปทรง อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| virtual **bool** [get_ShowBackground](./get_showbackground/)() | ดึงค่าที่ระบ่าว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่ อ่าน **bool** ค่าเริ่มต้น: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | คืนค่าสไลด์ฐาน อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | คืนค่าอ็อบเจกต์ [ThreeDFormat](../threedformat/) ที่บรรจุตามคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| virtual **float** [get_TransitionDuration](./get_transitionduration/)() | ดึงระยะเวลาในการเปลี่ยนภาพระหว่าง Zoom และสไลด์ อ่าน **float** ค่าเริ่มต้น: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | คืนค่า identifier ภายในที่จำกัดตามการนำเสนอซึ่งออกแบบมาสำหรับใช้โดย add-in หรือโค้ดอื่น ๆ เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม ควรไม่ถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร อ่านอย่างเดียว **uint32_t** ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/) |
| virtual **float** [get_Width](../ishape/get_width/)() | ดึงความกว้างของรูปทรงที่วัดเป็นจุด อ่าน **float** |
| virtual **float** [get_X](../ishape/get_x/)() | ดึงพิกัด x ของมุมซ้ายบนของรูปทรงที่วัดเป็นจุด อ่าน **float** |
| virtual **float** [get_Y](../ishape/get_y/)() | ดึงพิกัด y ของมุมซ้ายบนของรูปทรงที่วัดเป็นจุด อ่าน **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](./get_zoomimage/)() | ดึงภาพสำหรับวัตถุ zoom อ่าน [IPPImage](../ippimage/) |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | คืนค่าตำแหน่งของรูปทรงในลำดับ z Shapes[0] ให้รูปทรงที่อยู่ด้านหลังสุดของลำดับ z, และ Shapes[Shapes.Count - 1] ให้รูปทรงที่อยู่ด้านหน้าสุดของลำดับ z อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | คืนค่ารูปร่าง placeholder เบื้องต้น (รูปร่างจากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่รูปทรงปัจจุบันสืบทอดมา) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | ดึงโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ที่ทำให้สามารถแฮชวัตถุกำหนดเองได้ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | คืนค่าภาพย่อของรูปทรง [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ประเภทขอบเขตภาพย่อของรูปทรงถูกใช้เป็นค่าเริ่มต้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | คืนค่าภาพย่อของรูปทรง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | ดึงประเภทจริงของวัตถุ คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่ระบุโดย targetType หรือไม่ คล้ายกับโอเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ที่ทำให้สามารถโคลนประเภทกำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างวัตถุ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นวัตถุใหม่และเปิดให้สับคลาสย่อยคัดลอกได้ |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นวัตถุใหม่และเปิดให้สับคลาสย่อยคัดลอกได้ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุแบบ value type กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับการอ้างอิงร่วมโดยค่าที่ระบุ |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | ตั้งค่าข้อความแทนที่ที่เชื่อมโยงกับรูปทรง เขียน [System::String](../../system/string/) |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งค่าชื่อของข้อความแทนที่ที่เชื่อมโยงกับรูปทรง เขียน [System::String](../../system/string/) |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | คุณสมบัติกำหนดว่ารูปทรงจะแสดงอย่างไรในโหมดสีขาว-ดำ เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของเฟรมรูปทรง เขียน [IShapeFrame](../ishapeframe/) |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ตั้งค่าความสูงของรูปทรงที่วัดเป็นจุด เขียน **float** |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | กำหนดว่ารูปทรงซ่อนอยู่หรือไม่ เขียน **bool** |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่า hyperlink ที่กำหนดสำหรับคลิกเมาส์ เขียน [IHyperlink](../ihyperlink/) |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่า hyperlink ที่กำหนดสำหรับเมาส์อยู่เหนือ เขียน [IHyperlink](../ihyperlink/) |
| virtual void [set_ImageType](./set_imagetype/)([ZoomImageType](../zoomimagetype/)) | ตั้งค่าประเภทภาพของวัตถุ zoom เขียน [ZoomImageType](../zoomimagetype/) ค่าเริ่มต้น: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | ตั้งค่าชื่อของรูปทรง เขียน [System::String](../../system/string/) |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของเฟรมรูปทรงดิบ เขียน [IShapeFrame](../ishapeframe/) |
| virtual void [set_ReturnToParent](./set_returntoparent/)(**bool**) | ตั้งค่าพฤติกรรมการนำทางในสไลด์โชว์ เขียน **bool** ค่าเริ่มต้น: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | ตั้งค่าจำนวนองศาที่รูปทรงระบุหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา เขียน **float** |
| virtual void [set_ShowBackground](./set_showbackground/)(**bool**) | ตั้งค่าที่ระบ่าว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่ เขียน **bool** ค่าเริ่มต้น: true |
| virtual void [set_TransitionDuration](./set_transitionduration/)(**float**) | ตั้งค่าระยะเวลาการเปลี่ยนภาพระหว่าง Zoom และสไลด์ เขียน **float** ค่าเริ่มต้น: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | ตั้งค่าความกว้างของรูปทรงที่วัดเป็นจุด เขียน **float** |
| virtual void [set_X](../ishape/set_x/)(**float**) | ตั้งค่าพิกัด x ของมุมซ้ายบนของรูปทรงที่วัดเป็นจุด เขียน **float** |
| virtual void [set_Y](../ishape/set_y/)(**float**) | ตั้งค่าพิกัด y ของมุมซ้ายบนของรูปทรงที่วัดเป็นจุด เขียน **float** |
| virtual void [set_ZoomImage](./set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | ตั้งค่าภาพสำหรับวัตถุ zoom เขียน [IPPImage](../ippimage/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | ดึงค่าปัจจุบันของตัวนับการอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดตัวนับการอ้างอิงร่วมและคืนค่า ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ที่ทำให้สามารถแปลงวัตถุกำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ควรใช้ smart pointer หรือ ThisProtector |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IGraphicalObject](../igraphicalobject/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)