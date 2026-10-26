---
title: IZoomFrame
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนของออบเจ็กต์ Slide Zoom ในสไลด์
type: docs
weight: 4252
url: /th/aspose.slides/izoomframe/
---
## IZoomFrame คลาส

แสดงถึงวัตถุ [Slide](../slide/) Zoom ในสไลด์หนึ่ง

```cpp
class IZoomFrame : public virtual Aspose::Slides::IZoomObject
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติ placeholder ให้กับ placeholder ที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้การทำงานของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยตามสไตล์ของ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยตามสไตล์ของ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | คืนค่า alternative text ที่เชื่อมโยงกับ shape. อ่าน [System::String](../../system/string/) |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | คืนค่าชื่อเรื่องของ alternative text ที่เชื่อมโยงกับ shape. อ่าน [System::String](../../system/string/) |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Property ระบุว่ารูปจะถูกแสดงอย่างไรในโหมดสีขาว-ดำ. อ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | คืนค่าจำนวนจุดเชื่อมต่อบน shape. อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | คืนข้อมูล custom data ของ shape. อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | คืนออบเจ็กต์ [EffectFormat](../effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape. อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | คืนออบเจ็กต์ [FillFormat](../fillformat/) ที่มีคุณสมบัติการเติมสีสำหรับ shape. อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | คืนคุณสมบัติของกรอบ shape. อ่าน [IShapeFrame](../ishapeframe/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | คืนล็อกของ shape. อ่านอย่างเดียว [IGraphicalObjectLock](../igraphicalobjectlock/) |
| virtual **float** [get_Height](../ishape/get_height/)() | รับความสูงของ shape หน่วยเป็น points. อ่าน **float** |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | ตรวจสอบว่า shape ถูกซ่อนหรือไม่. อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | คืน hyperlink ที่กำหนดสำหรับการคลิกเมาส์. อ่าน [IHyperlink](../ihyperlink/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ตัวจัดการ hyperlink อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | คืน hyperlink ที่กำหนดสำหรับการเลื่อนเมาส์เหนือ. อ่าน [IHyperlink](../ihyperlink/) |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | รับประเภทภาพของวัตถุ zoom. อ่าน [ZoomImageType](../zoomimagetype/) ค่าเริ่มต้น: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | รับตัวเลือก ‘Mark as decorative’ อ่าน/เขียน **bool** |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | ตรวจสอบว่า shape ถูกจัดกลุ่มหรือไม่. อ่านอย่างเดียว **bool** |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | ตรวจสอบว่า shape เป็น TextHolder หรือไม่. อ่านอย่างเดียว **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | คืนออบเจ็กต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติการฟอร์แมตเส้นสำหรับ shape. อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | คืนชื่อของ shape. อ่าน [System::String](../../system/string/) |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | คืนหมายเลขประจำสไลด์ที่เป็นเอกลักษณ์และคงที่ตลอดอายุของ shape เพื่อให้ PowerPoint หรือโค้ด interop อ้างอิง shape ได้จากทุกที่ในเอกสาร. อ่านอย่างเดียว **uint32_t** ดูเพิ่มเติม [IShape::get_UniqueId](../ishape/get_uniqueid/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | คืนออบเจ็กต์ [GroupShape](../groupshape/) ของพาเรนต์ถ้า shape ถูกจัดกลุ่ม มิฉะนั้นคืน null. อ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | คืน placeholder ของ shape. อ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | คืนการนำเสนอ. อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | คืนคุณสมบัติกรอบ shape ดิบ. อ่าน [IShapeFrame](../ishapeframe/) |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | รับพฤติกรรมการนำทางในสไลด์โชว์. อ่าน **bool** ค่าเริ่มต้น: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | คืนจำนวนองศาที่ shape ถูกหมุนรอบแกน z. ค่าบวกบ่งบอกการหมุนตามเข็มนาฬิกา; ค่าลบบ่งบอกการหมุนทวนเข็มนาฬิกา. อ่าน **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | คืนล็อกของ shape. อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | รับค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์เป้าหมายหรือไม่. อ่าน **bool** ค่าเริ่มต้น: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | คืนสไลด์ฐาน. อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() | รับออบเจ็กต์สไลด์ที่ [Slide](../slide/) Zoom เชื่อมโยงไป. อ่าน [ISlide](../islide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | คืนออบเจ็กต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติการฟอร์แมตเส้นสำหรับ shape. อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | รับระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom กับสไลด์. อ่าน **float** ค่าเริ่มต้น: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | คืนหมายเลขประจำการนำเสนอภายในที่ใช้โดย add-ins หรือโค้ดอื่น ๆ. เนื่องจากค่านี้อาจถูกเปลี่ยนโดยผู้ใช้หรือโปรแกรม จึงไม่ควรใช้เป็นคีย์เอกลักษณ์ถาวร. อ่านอย่างเดียว **uint32_t** ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/) |
| virtual **float** [get_Width](../ishape/get_width/)() | รับความกว้างของ shape หน่วยเป็น points. อ่าน **float** |
| virtual **float** [get_X](../ishape/get_x/)() | รับพิกัด x ของมุมบนซ้ายของ shape หน่วยเป็น points. อ่าน **float** |
| virtual **float** [get_Y](../ishape/get_y/)() | รับพิกัด y ของมุมบนซ้ายของ shape หน่วยเป็น points. อ่าน **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | รับภาพสำหรับวัตถุ zoom. อ่าน [IPPImage](../ippimage/) |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | คืนตำแหน่งของ shape ในลำดับ z. Shapes[0] คืน shape ที่อยู่ด้านหลังสุดของลำดับ z, และ Shapes[Shapes.Count - 1] คืน shape ที่อยู่ด้านหน้า. อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | คืน placeholder shape พื้นฐาน (shape จากแม่แบบหรือสไลด์มาสเตอร์ที่ shape ปัจจุบันสืบทอดมา) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดการทำแฮชของออบเจ็กต์ custom |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | คืนภาพย่อของ shape. ชนิด bounds ของภาพย่อ [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ถูกใช้เป็นค่าเริ่มต้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | คืนภาพย่อของ shape |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์. Analogue ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. Analogue ของออปอเรเตอร์ C# 'is' |
| void [Lock](../../system/object/lock/)() | Implement คำสั่ง C# lock() สำหรับการล็อก. เรียกโดยตรงหรือใช้ออบเจ็กต์ sentry [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดการโคลนประเภท custom |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นออบเจ็กต์ใหม่และเปิดการคัดลอกของคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดการคัดลอกของคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | กำหนดว่า shape นี้ไม่ใช่ placeholder |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | ตั้งค่า alternative text ที่เชื่อมโยงกับ shape. เขียน [System::String](../../system/string/) |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งค่าชื่อเรื่องของ alternative text ที่เชื่อมโยงกับ shape. เขียน [System::String](../../system/string/) |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Property ระบุว่ารูปจะถูกแสดงอย่างไรในโหมดสีขาว-ดำ. เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติกรอบของ shape. เขียน [IShapeFrame](../ishapeframe/) |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ตั้งค่าความสูงของ shape หน่วยเป็น points. เขียน **float** |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | กำหนดว่า shape ถูกซ่อนหรือไม่. เขียน **bool** |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่า hyperlink ที่กำหนดสำหรับการคลิกเมาส์. เขียน [IHyperlink](../ihyperlink/) |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่า hyperlink ที่กำหนดสำหรับการเลื่อนเมาส์เหนือ. เขียน [IHyperlink](../ihyperlink/) |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | ตั้งค่าประเภทภาพของวัตถุ zoom. เขียน [ZoomImageType](../zoomimagetype/) ค่าเริ่มต้น: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ตั้งค่าตัวเลือก ‘Mark as decorative’ เขียน/อ่าน **bool** |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | ตั้งค่าชื่อของ shape. เขียน [System::String](../../system/string/) |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติกรอบของ shape ดิบ. เขียน [IShapeFrame](../ishapeframe/) |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | ตั้งค่าพฤติกรรมการนำทางในสไลด์โชว์. เขียน **bool** ค่าเริ่มต้น: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | ตั้งค่าจำนวนองศาที่ shape ถูกหมุนรอบแกน z. ค่าบวกบ่งบอกการหมุนตามเข็มนาฬิกา; ค่าลบบ่งบอกการหมุนทวนเข็มนาฬิกา. เขียน **float** |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | ตั้งค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์เป้าหมายหรือไม่. เขียน **bool** ค่าเริ่มต้น: true |
| virtual void [set_TargetSlide](./set_targetslide/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) | ตั้งค่าวัตถุสไลด์ที่ [Slide](../slide/) Zoom เชื่อมโยงไป. เขียน [ISlide](../islide/) |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | ตั้งค่าระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom กับสไลด์. เขียน **float** ค่าเริ่มต้น: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | ตั้งค่าความกว้างของ shape หน่วยเป็น points. เขียน **float** |
| virtual void [set_X](../ishape/set_x/)(**float**) | ตั้งค่าพิกัด x ของมุมบนซ้ายของ shape หน่วยเป็น points. เขียน **float** |
| virtual void [set_Y](../ishape/set_y/)(**float**) | ตั้งค่าพิกัด y ของมุมบนซ้ายของ shape หน่วยเป็น points. เขียน **float** |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | ตั้งค่าภาพสำหรับวัตถุ zoom. เขียน [IPPImage](../ippimage/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). รองรับการสลับ pointer ในคอนเทนเนอร์เป็น weak mode |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue ของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดการแปลงออบเจ็กต์ custom เป็น string |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implement C# typeof([System.Object](../../system/object/)) construct |
| void [Unlock](../../system/object/unlock/)() | Implement คำสั่ง C# lock() สำหรับการปลดล็อก. เรียกโดยตรงหรือใช้ออบเจ็กต์ sentry [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IZoomObject](../izoomobject/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)