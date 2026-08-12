---
title: IVideoFrame
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงถึงคลิปวิดีโอบนสไลด์.
type: docs
weight: 4226
url: /th/aspose.slides/ivideoframe/
---
## IVideoFrame คลาส

แสดงถึงคลิปวิดีโอบนสไลด์.

```cpp
class IVideoFrame : public virtual Aspose::Slides::IPictureFrame
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | สร้างและคืนค่าอาเรย์ของ shape's elements |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุชนิดอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุชนิดค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C#-style โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C#-style โดยที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | คืนค่าการปรับของ shape ณ ดัชนีที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | คืนคอลเลกชันของค่าการปรับของ shape. อ่านอย่างเดียว [IAdjustValueCollection](../iadjustvaluecollection/) |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | คืนข้อความแทนที่ที่เชื่อมโยงกับ shape. อ่าน [System::String](../../system/string/) |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | คืนหัวข้อของข้อความแทนที่ที่เชื่อมโยงกับ shape. อ่าน [System::String](../../system/string/) |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | คุณสมบัติเชื่อมโยงว่ารูปจะเรนเดอร์ในโหมดแสดงผลสีขาว-ดำอย่างไร. อ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | รับคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับ audio frame. คุณสมบัตินี้อ่านอย่างเดียวและคืนค่า [ICaptionsCollection](../icaptionscollection/) ที่บรรจุแทร็กคำบรรยายทั้งหมด |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | คืนจำนวนจุดเชื่อมต่อบน shape. อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | คืนข้อมูลกำหนดเองของ shape. อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | คืนวัตถุ [EffectFormat](../effectformat/) ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับ shape. อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_EmbeddedVideo](./get_embeddedvideo/)() | คืนวัตถุวิดีโอที่ฝังอยู่. อ่าน [IVideo](../ivideo/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | คืนวัตถุ [FillFormat](../fillformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบการเติมสีสำหรับ shape. อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | คืนคุณสมบัติของกรอบ shape. อ่าน [IShapeFrame](../ishapeframe/) |
| virtual **bool** [get_FullScreenMode](./get_fullscreenmode/)() | กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่. อ่าน **bool** |
| virtual **float** [get_Height](../ishape/get_height/)() | รับความสูงของ shape หน่วยเป็น points. อ่าน **float** |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | กำหนดว่า shape ถูกซ่อนไว้หรือไม่. อ่าน **bool** |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | กำหนดว่า [VideoFrame](../videoframe/) ถูกซ่อนไว้หรือไม่. อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | คืน hyperlink ที่กำหนดสำหรับคลิกเมาส์. อ่าน [IHyperlink](../ihyperlink/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ผู้จัดการ Hyperlinks อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | คืน hyperlink ที่กำหนดสำหรับเมาส์โอเวอร์. อ่าน [IHyperlink](../ihyperlink/) |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | กำหนดว่า shape ถูกจัดเป็นกลุ่มหรือไม่. อ่านแบบอ่านอย่างเดียว **bool** |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | กำหนดว่า shape เป็น TextHolder หรือไม่. อ่านแบบอ่านอย่างเดียว **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | คืนวัตถุ [LineFormat](../lineformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape. อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | คืนชื่อไฟล์วิดีโอที่เชื่อมโยงกับ [VideoFrame](../videoframe/). อ่าน [System::String](../../system/string/) |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | คืนชื่อของ shape. อ่าน [System::String](../../system/string/) |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | คืนตัวระบุที่ไม่ซ้ำเฉพาะสไลด์ซึ่งคงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้อย่างเชื่อถือจากทุกตำแหน่งในเอกสาร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_UniqueId](../ishape/get_uniqueid/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | คืน parent [GroupShape](../groupshape/) object หาก shape ถูกจัดเป็นกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | คืนวัตถุ [PictureFillFormat](../picturefillformat/) สำหรับ picture frame. อ่านอย่างเดียว [IPictureFillFormat](../ipicturefillformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | คืน [PictureFrame](../pictureframe/)'s locks. อ่านอย่างเดียว [IPictureFrameLock](../ipictureframelock/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | คืน placeholder สำหรับ shape. อ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | กำหนดว่าวิดีโอจะเล่นซ้ำหรือไม่. อ่าน **bool** |
| virtual [VideoPlayModePreset](../videoplaymodepreset/) [get_PlayMode](./get_playmode/)() | คืนโหมดการเล่นวิดีโอ. อ่าน [VideoPlayModePreset](../videoplaymodepreset/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | คืนพรีเซนเทชัน. อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | คืนคุณสมบัติ raw shape frame. อ่าน [IShapeFrame](../ishapeframe/) |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | คืนอัตราส่วนความสูง (เทียบกับขนาดภาพต้นฉบับ) ของกรอบภาพ. ค่า 1.0 เท่ากับ 100%. อ่าน **float** |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | คืนอัตราส่วนความกว้าง (เทียบกับขนาดภาพต้นฉบับ) ของกรอบภาพ. ค่า 1.0 เท่ากับ 100%. อ่าน **float** |
| virtual **bool** [get_RewindVideo](./get_rewindvideo/)() | กำหนดว่าวิดีโอจะรีวินด์อัตโนมัติเมื่อจบการเล่นหรือไม่. อ่าน **bool** |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | คืนจำนวนองศาที่ shape ถูกหมุนรอบแกน z. ค่าเชิงบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเชิงลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | คืน locks ของ shape. อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | คืนอ็อบเจกต์ style ของ shape. อ่านอย่างเดียว [IShapeStyle](../ishapestyle/) |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | คืนประเภท preset ของ geometry. หมายเหตุ: เมื่อค่าเปลี่ยน ค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น. อ่าน [Slides::ShapeType](../shapetype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | คืนสไลด์ฐาน. อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | คืนวัตถุ [ThreeDFormat](../threedformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape. อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | ตัดท้าย [ms] |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | ตัดเริ่มต้น [ms] |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | คืนตัวระบุภายในที่ใช้ในระดับพรีเซนเทชันสำหรับใช้โดย add-ins หรือโค้ดอื่น ๆ เนื่องจากค่านี้สามารถถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรมได้ จึงไม่ควรถือเป็นคีย์ที่ไม่ซ้ำแบบถาวร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/) |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | คืนระดับเสียงของ audio. อ่าน [AudioVolumeMode](../audiovolumemode/) |
| virtual **float** [get_Width](../ishape/get_width/)() | รับความกว้างของ shape หน่วยเป็น points. อ่าน **float** |
| virtual **float** [get_X](../ishape/get_x/)() | รับค่า x-coordinate ของมุมซ้ายบนของ shape หน่วยเป็น points. อ่าน **float** |
| virtual **float** [get_Y](../ishape/get_y/)() | รับค่า y-coordinate ของมุมซ้ายบนของ shape หน่วยเป็น points. อ่าน **float** |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | คืนตำแหน่งของ shape ใน z-order. Shapes[0] คืน shape ที่อยู่ด้านหลังของ z-order, และ Shapes[Shapes.Count - 1] คืน shape ที่อยู่ด้านหน้าของ z-order. อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | คืน shape placeholder พื้นฐาน (shape จาก layout และ/หรือ master slide ที่ shape ปัจจุบันสืบทอดมาจาก) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | คืนสำเนา path ของ geometry shape. พิกัดสัมพันธ์กับมุมซ้ายบนของ shape |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | คืน thumbnail ของ shape. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) shape thumbnail bounds type is used by default |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | คืน thumbnail ของ shape |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. Analog of C# [System.Object.GetType()](../../system/object/gettype/) call |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. Analog of C# 'is' operator |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. Initialise all internal data structures |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Reference-compares value type object with nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of string and nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialization of [Object::ReferenceEquals](../../system/object/referenceequals/) for case of strings |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | กำหนดว่า shape นี้ไม่ได้เป็น placeholder |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | ตั้งข้อความแทนที่ที่เชื่อมโยงกับ shape. Write [System::String](../../system/string/) |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งหัวข้อของข้อความแทนที่ที่เชื่อมโยงกับ shape. Write [System::String](../../system/string/) |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Property specifies how a shape will render in black-and-white display mode.. Write [Slides::BlackWhiteMode](../blackwhitemode/) |
| virtual void [set_EmbeddedVideo](./set_embeddedvideo/)([System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) | ตั้งวัตถุวิดีโอที่ฝังอยู่. Write [IVideo](../ivideo/) |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งคุณสมบัติของกรอบ shape. Write [IShapeFrame](../ishapeframe/) |
| virtual void [set_FullScreenMode](./set_fullscreenmode/)(**bool**) | กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่. Write **bool** |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ตั้งความสูงของ shape หน่วยเป็น points. Write **float** |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | กำหนดว่า shape ถูกซ่อนไว้หรือไม่. Write **bool** |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | กำหนดว่า [VideoFrame](../videoframe/) ถูกซ่อนไว้หรือไม่. Write **bool** |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้ง hyperlink ที่กำหนดสำหรับคลิกเมาส์. Write [IHyperlink](../ihyperlink/) |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้ง hyperlink ที่กำหนดสำหรับเมาส์โอเวอร์. Write [IHyperlink](../ihyperlink/) |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ตั้งตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | ตั้งชื่อไฟล์วิดีโอที่เชื่อมโยงกับ [VideoFrame](../videoframe/). Write [System::String](../../system/string/) |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | ตั้งชื่อของ shape. Write [System::String](../../system/string/) |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | กำหนดว่าวิดีโอจะเล่นซ้ำหรือไม่. Write **bool** |
| virtual void [set_PlayMode](./set_playmode/)([VideoPlayModePreset](../videoplaymodepreset/)) | ตั้งโหมดการเล่นวิดีโอ. Write [VideoPlayModePreset](../videoplaymodepreset/) |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งคุณสมบัติ raw shape frame. Write [IShapeFrame](../ishapeframe/) |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | ตั้งอัตราส่วนความสูง (เทียบกับขนาดภาพต้นฉบับ) ของกรอบภาพ. ค่า 1.0 เท่ากับ 100%. Write **float** |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | ตั้งอัตราส่วนความกว้าง (เทียบกับขนาดภาพต้นฉบับ) ของกรอบภาพ. ค่า 1.0 เท่ากับ 100%. Write **float** |
| virtual void [set_RewindVideo](./set_rewindvideo/)(**bool**) | กำหนดว่าวิดีโอจะรีวินด์อัตโนมัติเมื่อจบการเล่นหรือไม่. Write **bool** |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | ตั้งจำนวนองศาที่ shape ถูกหมุนรอบแกน z. ค่าเชิงบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเชิงลบหมายถึงการหมุนทวนเข็มนาฬิกา. Write **float** |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | ตั้งประเภท preset ของ geometry. หมายเหตุ: เมื่อค่าเปลี่ยน ค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น. Write [Slides::ShapeType](../shapetype/) |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | ตัดท้าย [ms] |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | ตัดเริ่มต้น [ms] |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | ตั้งระดับเสียงของ audio. Write [AudioVolumeMode](../audiovolumemode/) |
| virtual void [set_Width](../ishape/set_width/)(**float**) | ตั้งความกว้างของ shape หน่วยเป็น points. Write **float** |
| virtual void [set_X](../ishape/set_x/)(**float**) | ตั้งค่า x-coordinate ของมุมซ้ายบนของ shape หน่วยเป็น points. Write **float** |
| virtual void [set_Y](../ishape/set_y/)(**float**) | ตั้งค่า y-coordinate ของมุมซ้ายบนของ shape หน่วยเป็น points. Write **float** |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | อัปเดต geometry ของ shape จากวัตถุ [IGeometryPath](../igeometrypath/). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/) |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | อัปเดต geometry ของ shape จากอาร์เรย์ของ [IGeometryPath](../igeometrypath/). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทนการเป็น shared). อนุญาตให้สลับ pointer ใน container ไปเป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## ดูเพิ่มเติม

* คลาส [IPictureFrame](../ipictureframe/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)