---
title: VideoFrame
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงคลิปวิดีโอบนสไลด์.
type: docs
weight: 5552
url: /th/aspose.slides/videoframe/
---
## VideoFrame คลาส

Represents a video clip on a slide.

```cpp
class VideoFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IVideoFrame
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | เพิ่มตำแหน่งชั่วคราวใหม่หากไม่มีและตั้งค่าคุณสมบัติตำแหน่งชั่วคราวให้เป็นค่าที่ระบุ |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | สร้างและส่งคืนอาร์เรย์ขององค์ประกอบของรูปร่าง |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ของ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ของ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | ส่งคืนค่าการปรับของรูปร่างที่ตำแหน่งที่ระบุ |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | ส่งคืนคอลเลกชันของค่าการปรับของรูปร่าง อ่านอย่างเดียว [IAdjustValueCollection](../iadjustvaluecollection/) |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | ส่งคืนข้อความแทนที่เชื่อมโยงกับรูปร่าง อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | ส่งคืนชื่อของข้อความแทนที่เชื่อมโยงกับรูปร่าง อ่าน [System::String](../../system/string/) |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | คุณลักษณะระบุว่ารูปร่างจะแสดงผลอย่างไรในโหมดสีดำ-ขาว อ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | รับคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับเฟรมวีดีโอ คุณลักษณะนี้เป็นอ่านอย่างเดียวและส่งคืน [ICaptionsCollection](../icaptionscollection/) ที่มีแทร็กคำบรรยายทั้งหมด |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | ส่งคืนจำนวนจุดเชื่อมต่อบนรูปร่าง อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | ส่งคืนข้อมูลกำหนดเองของรูปร่าง อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | ส่งคืนอ็อบเจกต์ [EffectFormat](../effectformat/) ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง หมายเหตุ: อาจส่งคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์ อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_EmbeddedVideo](./get_embeddedvideo/)() override | ส่งคืนอ็อบเจกต์วิดีโอที่ฝังอยู่ อ่าน [IVideo](../ivideo/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | ส่งคืนอ็อบเจกต์ [FillFormat](../fillformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบการเติมสีสำหรับรูปร่าง หมายเหตุ: อาจส่งคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติมสี อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | ส่งคืนคุณสมบัติของเฟรมรูปร่าง อ่าน [IShapeFrame](../ishapeframe/) |
| **bool** [get_FullScreenMode](./get_fullscreenmode/)() override | กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่ อ่าน **bool** |
| **float** [get_Height](../shape/get_height/)() override | รับความสูงของรูปร่างวัดเป็นจุด อ่าน **float** |
| **bool** [get_Hidden](../shape/get_hidden/)() override | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ อ่าน **bool** |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | กำหนดว่า [VideoFrame](./) ถูกซ่อนหรือไม่ อ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | ส่งคืนไฮเพอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์ อ่าน [IHyperlink](../ihyperlink/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | ส่งคืนผู้จัดการไฮเพอร์ลิงก์ อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | ส่งคืนไฮเพอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ อ่าน [IHyperlink](../ihyperlink/) |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | กำหนดว่า [PictureFrame](../pictureframe/) เป็นอ็อบเจกต์ Cameo หรือไม่ อ่านอย่างเดียว **bool** |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่ อ่านอย่างเดียว **bool** |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | ส่งคืนอ็อบเจกต์ [LineFormat](../lineformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง หมายเหตุ: อาจส่งคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเส้น อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | ส่งคืนชื่อไฟล์วิดีโอที่เชื่อมโยงกับ [VideoFrame](./) อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | ส่งคืนชื่อของรูปร่าง ต้องไม่เป็น null ใช้ค่าสตริงว่างหากจำเป็น อ่าน [System::String](../../system/string/) |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | ส่งคืนตัวระบุเอกลักษณ์ระดับสไลด์ที่คงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างจากที่ใดก็ได้ในเอกสาร อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_UniqueId](../shape/get_uniqueid/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | ส่งคืนอ็อบเจกต์ [GroupShape](../groupshape/) พาเรนต์หากรูปร่างเป็นกลุ่ม มิฉะนั้นส่งคืนค่า null อ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | ส่งคืนอ็อบเจกต์ [PictureFillFormat](../picturefillformat/) สำหรับเฟรมรูปภาพ อ่านอย่างเดียว [IPictureFillFormat](../ipicturefillformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | ส่งคืนการล็อกของรูปร่าง อ่านอย่างเดียว [IPictureFrameLock](../ipictureframelock/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | ส่งคืน placeholder ของรูปร่าง ส่งคืน null หากรูปร่างไม่มี placeholder อ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | กำหนดว่าวิดีโอวนซ้ำหรือไม่ อ่าน **bool** |
| [VideoPlayModePreset](../videoplaymodepreset/) [get_PlayMode](./get_playmode/)() override | ส่งคืนโหมดการเล่นวิดีโอ อ่าน [VideoPlayModePreset](../videoplaymodepreset/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | ส่งคืนการนำเสนอพาเรนต์ของสไลด์ อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | ส่งคืนคุณสมบัติของเฟรมรูปร่างดิบ อ่าน [IShapeFrame](../ishapeframe/) |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | ส่งคืนสเกลความสูง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของเฟรมรูปภาพ ค่า 1.0 ตรงกับ 100% อ่าน **float** |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | ส่งคืนสเกลความกว้าง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของเฟรมรูปภาพ ค่า 1.0 ตรงกับ 100% อ่าน **float** |
| **bool** [get_RewindVideo](./get_rewindvideo/)() override | กำหนดว่าวิดีโอจะรีวินด์อัตโนมัติไปยังจุดเริ่มต้นทันทีที่ภาพยนตร์เล่นจบหรือไม่ อ่าน **bool** |
| **float** [get_Rotation](../shape/get_rotation/)() override | ส่งคืนจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z ค่าเป็นบวกหมายถึงหมุนตามเข็มนาฬิกา ค่าเป็นลบหมายถึงหมุนทวนเข็มนาฬิกา อ่าน **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | ส่งคืนการล็อกของรูปร่าง อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | ส่งคืนอ็อบเจกต์สไตล์ของรูปร่าง อ่านอย่างเดียว [IShapeStyle](../ishapestyle/) |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | ส่งคืนสไลด์พาเรนต์ของรูปร่าง อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | ส่งคืนอ็อบเจกต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติเพรด 3 มิติของรูปร่าง หมายเหตุ: อาจส่งคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | ตัดส่วนท้าย [ms] |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | ตัดส่วนเริ่มต้น [ms] |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | ส่งคืนตัวระบุภายในระดับการนำเสนอที่ออกแบบไว้สำหรับใช้โดยแอด-อินหรือโค้ดอื่น เนื่องจากค่านี้อาจถูกกำหนดค่าใหม่โดยผู้ใช้หรือโดยโปรแกรม จึงไม่ควรถือว่าเป็นคีย์เอกลักษณ์ถาวร อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/) |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | ส่งคืนระดับเสียงของออดิโอ อ่าน [AudioVolumeMode](../audiovolumemode/) |
| **float** [get_Width](../shape/get_width/)() override | รับความกว้างของรูปร่างวัดเป็นจุด อ่าน **float** |
| **float** [get_X](../shape/get_x/)() override | รับค่าพิกัด x ของมุมซ้ายบนของรูปร่างวัดเป็นจุด อ่าน **float** |
| **float** [get_Y](../shape/get_y/)() override | รับค่าพิกัด y ของมุมซ้ายบนของรูปร่างวัดเป็นจุด อ่าน **float** |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | ส่งคืนตำแหน่งของรูปร่างในลำดับ z Shapes[0] ส่งคืนรูปร่างที่อยู่ด้านหลังของลำดับ z และ Shapes[Shapes.Count - 1] ส่งคืนรูปร่างที่อยู่ด้านหน้าของลำดับ z อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | ส่งคืนรูปร่าง placeholder พื้นฐาน (รูปร่างจากเลเอาต์และ/หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอดมา) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | ส่งคืนสำเนาของเส้นทางของรูปร่างเรขาคณิต พิกัดสัมพันธ์กับมุมซ้ายบนของรูปร่าง |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชวัตถุกำหนดเองได้ |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | ส่งคืนรูปย่อของรูปร่าง [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ประเภทขอบเขตรูปย่อของรูปร่างถูกใช้เป็นค่าเริ่มต้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | ส่งคืนรูปย่อของรูปร่าง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจกต์ เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | รับขอบเขตการแสดงผลของรูปร่างที่คำนวนจากเนื้อหาที่เรนเดอร์ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType เป็นอนาล็อกของออเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทกำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์สำเนา ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และอนุญาตให้สร้างสำเนาในคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และอนุญาตให้สร้างสำเนาในคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่ใช้ร่วมกันตามค่าที่ระบุ |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | ตั้งค่าข้อความแทนที่เชื่อมโยงกับรูปร่าง เขียน [System::String](../../system/string/) |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | ตั้งค่าชื่อของข้อความแทนที่เชื่อมโยงกับรูปร่าง เขียน [System::String](../../system/string/) |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | คุณลักษณะระบุว่ารูปร่างจะแสดงผลอย่างไรในโหมดสีดำ-ขาว เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| void [set_EmbeddedVideo](./set_embeddedvideo/)([System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) override | ตั้งค่าอ็อบเจกต์วิดีโอที่ฝังอยู่ เขียน [IVideo](../ivideo/) |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของเฟรมรูปร่าง เขียน [IShapeFrame](../ishapeframe/) |
| void [set_FullScreenMode](./set_fullscreenmode/)(**bool**) override | กำหนดว่าวิดีโอจะแสดงในโหมดเต็มหน้าจอหรือไม่ เขียน **bool** |
| void [set_Height](../shape/set_height/)(**float**) override | ตั้งค่าความสูงของรูปร่างวัดเป็นจุด เขียน **float** |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ เขียน **bool** |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | กำหนดว่า [VideoFrame](./) ถูกซ่อนหรือไม่ เขียน **bool** |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าไฮเพอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์ เขียน [IHyperlink](../ihyperlink/) |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าไฮเพอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ เขียน [IHyperlink](../ihyperlink/) |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | ตั้งค่าชื่อไฟล์วิดีโอที่เชื่อมโยงกับ [VideoFrame](./) เขียน [System::String](../../system/string/) |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | ตั้งค่าชื่อของรูปร่าง ต้องไม่เป็น null ใช้ค่าสตริงว่างหากจำเป็น เขียน [System::String](../../system/string/) |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | กำหนดว่าวิดีโอวนซ้ำหรือไม่ เขียน **bool** |
| void [set_PlayMode](./set_playmode/)([VideoPlayModePreset](../videoplaymodepreset/)) override | ตั้งค่าโหมดเล่นวิดีโอ เขียน [VideoPlayModePreset](../videoplaymodepreset/) |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของเฟรมรูปร่างดิบ เขียน [IShapeFrame](../ishapeframe/) |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | ตั้งค่าสเกลความสูง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของเฟรมรูปภาพ ค่า 1.0 ตรงกับ 100% เขียน **float** |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | ตั้งค่าสเกลความกว้าง (สัมพันธ์กับขนาดภาพต้นฉบับ) ของเฟรมรูปภาพ ค่า 1.0 ตรงกับ 100% เขียน **float** |
| void [set_RewindVideo](./set_rewindvideo/)(**bool**) override | กำหนดว่าวิดีโอจะรีวินด์อัตโนมัติไปยังจุดเริ่มต้นทันทีที่ภาพยนตร์เล่นจบหรือไม่ เขียน **bool** |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | ตั้งค่าจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z ค่าเป็นบวกหมายถึงหมุนตามเข็มนาฬิกา ค่าเป็นลบหมายถึงหมุนทวนเข็มนาฬิกา เขียน **float** |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | ตัดส่วนท้าย [ms] |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | ตัดส่วนเริ่มต้น [ms] |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | ตั้งค่าระดับเสียงออดิโอ เขียน [AudioVolumeMode](../audiovolumemode/) |
| void [set_Width](../shape/set_width/)(**float**) override | ตั้งค่าความกว้างของรูปร่างวัดเป็นจุด เขียน **float** |
| void [set_X](../shape/set_x/)(**float**) override | ตั้งค่าพิกัด x ของมุมซ้ายบนของรูปร่างวัดเป็นจุด เขียน **float** |
| void [set_Y](../shape/set_y/)(**float**) override | ตั้งค่าพิกัด y ของมุมซ้ายบนของรูปร่างวัดเป็นจุด เขียน **float** |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | อัปเดตเรขาคณิตของรูปร่างจากอ็อบเจกต์ [IGeometryPath](../igeometrypath/) พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปร่าง เปลี่ยนประเภทของรูปร่าง ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/) |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | อัปเดตเรขาคณิตของรูปร่างจากอาร์เรย์ของ [IGeometryPath](../igeometrypath/) พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปร่าง เปลี่ยนประเภทของรูปร่าง ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | กำหนดอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (ไม่ใช่ shared) อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่ใช้ร่วมกัน |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งคืนตัวนับการอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงวัตถุกำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็น construct ของ C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [PictureFrame](../pictureframe/)
* คลาส [IVideoFrame](../ivideoframe/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)