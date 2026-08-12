---
title: IAudioFrame
second_title: Aspose.Slides สำหรับ C++ API เอกสารอ้างอิง
description: แสดงคลิปเสียงบนสไลด์.
type: docs
weight: 1353
url: /th/aspose.slides/iaudioframe/
---
## IAudioFrame คลาส

แสดงคลิปเสียงบนสไลด์.

```cpp
class IAudioFrame : public virtual Aspose::Slides::IPictureFrame
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าเฉพาะที่ระบุ |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | สร้างและคืนค่าอาเรย์ขององค์ประกอบของ shape |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าทศนิยมแบบ C# ที่ NaN สองค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าทศนิยมแบบ C# ที่ NaN สองค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | คืนค่าการปรับแต่งของ shape ที่ตำแหน่งที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | คืนคอลเลกชันของค่าการปรับแต่งของ shape. อ่านอย่างเดียว [IAdjustValueCollection](../iadjustvaluecollection/). |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | คืนข้อความแทนที่เชื่อมโยงกับ shape. อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | คืนชื่อเรื่องของข้อความแทนที่เชื่อมโยงกับ shape. อ่าน [System::String](../../system/string/). |
| virtual **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() | คืนค่าดัชนีแทร็กสุดท้าย อ่าน **int32_t**. |
| virtual **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() | คืนค่าเวลาของแทร็กสุดท้าย อ่าน **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() | คืนค่าดัชนีแทร็กเริ่มต้น อ่าน **int32_t**. |
| virtual **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() | คืนค่าเวลาของแทร็กเริ่มต้น อ่าน **int32_t**. |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | คุณสมบัติระบุว่ารูปร่างจะเรนเดอร์อย่างไรในโหมดแสดงผลขาว-ดำ. อ่าน [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | รับคอลเลกชันของคำบรรยายปิดที่เชื่อมโยงกับ audio frame. คุณสมบัตินี้เป็นแบบอ่านอย่างเดียวและคืนค่า [ICaptionsCollection](../icaptionscollection/) ที่มีแทร็กคำบรรยายทั้งหมด. |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | คืนจำนวนจุดเชื่อมต่อบน shape. อ่านอย่างเดียว **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | คืนข้อมูลที่กำหนดเองของ shape. อ่านอย่างเดียว [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | คืนอ็อบเจ็กต์ [EffectFormat](../effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape. อ่านอย่างเดียว [IEffectFormat](../ieffectformat/). |
| virtual **bool** [get_Embedded](./get_embedded/)() | กำหนดว่ามีเสียงฝังอยู่ในงานนำเสนอหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() | คืนอ็อบเจ็กต์เสียงที่ฝังอยู่. อ่าน [IAudio](../iaudio/). |
| virtual **float** [get_FadeInDuration](./get_fadeinduration/)() | ระบุระยะเวลา (มิลลิวินาที) ของการเฟดอินเริ่มต้นของสื่อ. อ่าน **float**. |
| virtual **float** [get_FadeOutDuration](./get_fadeoutduration/)() | ระบุระยะเวลา (มิลลิวินาที) ของการเฟดเอาต์สุดท้ายของสื่อ. อ่าน **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | คืนอ็อบเจ็กต์ [FillFormat](../fillformat/) ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับ shape. อ่านอย่างเดียว [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | คืนคุณสมบัติของเฟรม shape. อ่าน [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Height](../ishape/get_height/)() | รับความสูงของ shape หน่วยเป็น points. อ่าน **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | กำหนดว่า shape ถูกซ่อนหรือไม่. อ่าน **bool**. |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | กำหนดว่า [AudioFrame](../audioframe/) ถูกซ่อนหรือไม่. อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | คืน hyperlink ที่กำหนดสำหรับการคลิกเมาส์. อ่าน [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ผู้จัดการ hyperlink (อ่านอย่างเดียว) [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | คืน hyperlink ที่กำหนดสำหรับการชี้เมาส์. อ่าน [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | รับตัวเลือก 'Mark as decorative' (อ่าน/เขียน) **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | กำหนดว่า shape เป็น TextHolder หรือไม่. อ่านอย่างเดียว **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | คืนอ็อบเจ็กต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape. อ่านอย่างเดียว [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | คืนชื่อไฟล์เสียงที่เชื่อมโยงกับ [AudioFrame](../audioframe/). อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | คืนชื่อของ shape. อ่าน [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | คืนตัวระบุที่ไม่ซ้ำกันระดับสไลด์ซึ่งคงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้อย่างมั่นใจจากทุกที่ในเอกสาร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | คืนอ็อบเจ็กต์พาเรนท์ [GroupShape](../groupshape/) หาก shape ถูกจัดกลุ่ม มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | คืนอ็อบเจ็กต์ [PictureFillFormat](../picturefillformat/) สำหรับ picture frame. อ่านอย่างเดียว [IPictureFillFormat](../ipicturefillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | คืนล็อกของ [PictureFrame](../pictureframe/). อ่านอย่างเดียว [IPictureFrameLock](../ipictureframelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | คืน placeholder สำหรับ shape. อ่านอย่างเดียว [IPlaceholder](../iplaceholder/). |
| virtual **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() | กำหนดว่าเสียงกำลังเล่นข้ามสไลด์หรือไม่. อ่าน **bool**. |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | กำหนดว่าเสียงวนซ้ำหรือไม่. อ่าน **bool**. |
| virtual [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() | คืนโหมดการเล่นเสียง. อ่าน [AudioPlayModePreset](../audioplaymodepreset/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | คืนการนำเสนอ. อ่านอย่างเดียว [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | คืนคุณสมบัติดิบของเฟรม shape. อ่าน [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | คืนอัตราส่วนความสูง (เทียบกับขนาดภาพต้นฉบับ) ของ picture frame. ค่า 1.0 หมายถึง 100%. อ่าน **float**. |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | คืนอัตราส่วนความกว้าง (เทียบกับขนาดภาพต้นฉบับ) ของ picture frame. ค่า 1.0 หมายถึง 100%. อ่าน **float**. |
| virtual **bool** [get_RewindAudio](./get_rewindaudio/)() | กำหนดว่าเสียงจะกลับไปเริ่มต้นโดยอัตโนมัติหลังการเล่นหรือไม่. อ่าน **bool**. |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | คืนจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | คืนล็อกของ shape. อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | คืนอ็อบเจ็กต์สไตล์ของ shape. อ่านอย่างเดียว [IShapeStyle](../ishapestyle/). |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | คืนประเภท geometry preset. หมายเหตุ: เมื่อเปลี่ยนค่า ค่าการปรับแต่งทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น. อ่าน [Slides::ShapeType](../shapetype/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | คืนสไลด์ฐาน. อ่านอย่างเดียว [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | คืนอ็อบเจ็กต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape. อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | ระบุระยะเวลา (มิลลิวินาที) ที่ต้องตัดออกจากส่วนท้ายของสื่อระหว่างการเล่น. อ่าน **float**. |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | ระบุระยะเวลา (มิลลิวินาที) ที่ต้องตัดออกจากส่วนต้นของสื่อระหว่างการเล่น. อ่าน **float**. |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | คืนตัวระบุภายในระดับการนำเสนอซึ่งตั้งใจให้ใช้โดย add-in หรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกเปลี่ยนโดยผู้ใช้หรือโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่คงที่และไม่ซ้ำกัน. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | คืนระดับเสียง. อ่าน [AudioVolumeMode](../audiovolumemode/). |
| virtual **float** [get_VolumeValue](./get_volumevalue/)() | คืนระดับเสียงเป็นเปอร์เซ็นต์. อ่าน **float**. |
| virtual **float** [get_Width](../ishape/get_width/)() | รับความกว้างของ shape หน่วยเป็น points. อ่าน **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | รับพิกัด x ของมุมซ้ายบนของ shape หน่วยเป็น points. อ่าน **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | รับพิกัด y ของมุมซ้ายบนของ shape หน่วยเป็น points. อ่าน **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | คืนตำแหน่งของ shape ในลำดับ z. Shapes[0] คืน shape ที่อยู่ด้านหลังสุดของลำดับ z, และ Shapes[Shapes.Count - 1] คืน shape ที่อยู่ด้านหน้าสุดของลำดับ z. อ่านอย่างเดียว **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | คืน shape placeholder พื้นฐาน (shape จากเลเอาต์และ/หรือสไลด์แม่ที่ shape ปัจจุบันสืบทอดมา) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | คืนสำเนาของเส้นทางของ geometry shape. พิกัดอ้างอิงจากมุมซ้ายบนของ shape |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | คืน thumbnail ของ shape. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ชนิดขอบเขต thumbnail ของ shape จะถูกใช้โดยค่าเริ่มต้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | คืน thumbnail ของ shape |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับออปเครเตอร์ C# 'is' |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentinel |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์แบบค่า กับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมลงตามค่าที่ระบุ |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | กำหนดว่า shape นี้ไม่ใช่ placeholder |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | ตั้งข้อความแทนที่เชื่อมโยงกับ shape. เขียน [System::String](../../system/string/) |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งชื่อเรื่องของข้อความแทนที่เชื่อมโยงกับ shape. เขียน [System::String](../../system/string/) |
| virtual void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) | ตั้งค่าดัชนีแทร็กสุดท้าย เขียน **int32_t** |
| virtual void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) | ตั้งค่าเวลาของแทร็กสุดท้าย เขียน **int32_t** |
| virtual void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) | ตั้งค่าดัชนีแทร็กเริ่มต้น เขียน **int32_t** |
| virtual void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) | ตั้งค่าเวลาของแทร็กเริ่มต้น เขียน **int32_t** |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | คุณสมบัติระบุว่ารูปร่างจะเรนเดอร์อย่างไรในโหมดแสดงผลขาว-ดำ. เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| virtual void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | ตั้งค่าอ็อบเจ็กต์เสียงที่ฝังอยู่. เขียน [IAudio](../iaudio/) |
| virtual void [set_FadeInDuration](./set_fadeinduration/)(**float**) | ระบุระยะเวลา (มิลลิวินาที) ของการเฟดอินเริ่มต้นของสื่อ. เขียน **float** |
| virtual void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) | ระบุระยะเวลา (มิลลิวินาที) ของการเฟดเอาต์สุดท้ายของสื่อ. เขียน **float** |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของเฟรม shape. เขียน [IShapeFrame](../ishapeframe/) |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ตั้งค่าความสูงของ shape หน่วยเป็น points. เขียน **float** |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | กำหนดว่า shape ถูกซ่อนหรือไม่. เขียน **bool** |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | กำหนดว่า [AudioFrame](../audioframe/) ถูกซ่อนหรือไม่. เขียน **bool** |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่า hyperlink ที่กำหนดสำหรับการคลิกเมาส์. เขียน [IHyperlink](../ihyperlink/) |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่า hyperlink ที่กำหนดสำหรับการชี้เมาส์. เขียน [IHyperlink](../ihyperlink/) |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ตั้งค่าตัวเลือก 'Mark as decorative' (อ่าน/เขียน) **bool** |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | ตั้งชื่อไฟล์เสียงที่เชื่อมโยงกับ [AudioFrame](../audioframe/). เขียน [System::String](../../system/string/) |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | ตั้งชื่อของ shape. เขียน [System::String](../../system/string/) |
| virtual void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) | กำหนดว่าเสียงกำลังเล่นข้ามสไลด์หรือไม่. เขียน **bool** |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | กำหนดว่าเสียงวนซ้ำหรือไม่. เขียน **bool** |
| virtual void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) | ตั้งค่าโหมดการเล่นเสียง. เขียน [AudioPlayModePreset](../audioplaymodepreset/) |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติดิบของเฟรม shape. เขียน [IShapeFrame](../ishapeframe/) |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | ตั้งค่าอัตราส่วนความสูง (เทียบกับขนาดภาพต้นฉบับ) ของ picture frame. ค่า 1.0 หมายถึง 100%. เขียน **float** |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | ตั้งค่าอัตราส่วนความกว้าง (เทียบกับขนาดภาพต้นฉบับ) ของ picture frame. ค่า 1.0 หมายถึง 100%. เขียน **float** |
| virtual void [set_RewindAudio](./set_rewindaudio/)(**bool**) | กำหนดว่าเสียงจะกลับไปเริ่มต้นโดยอัตโนมัติหลังการเล่นหรือไม่. เขียน **bool** |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | ตั้งค่าจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. เขียน **float** |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | ตั้งค่าชนิด geometry preset. หมายเหตุ: เมื่อเปลี่ยนค่า ค่าการปรับแต่งทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น. เขียน [Slides::ShapeType](../shapetype/) |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | ระบุระยะเวลา (มิลลิวินาที) ที่ต้องตัดออกจากส่วนท้ายของสื่อระหว่างการเล่น. เขียน **float** |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | ระบุระยะเวลา (มิลลิวินาที) ที่ต้องตัดออกจากส่วนต้นของสื่อระหว่างการเล่น. เขียน **float** |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | ตั้งระดับเสียง. เขียน [AudioVolumeMode](../audiovolumemode/) |
| virtual void [set_VolumeValue](./set_volumevalue/)(**float**) | ตั้งระดับเสียงเป็นเปอร์เซ็นต์. เขียน **float** |
| virtual void [set_Width](../ishape/set_width/)(**float**) | ตั้งความกว้างของ shape หน่วยเป็น points. เขียน **float** |
| virtual void [set_X](../ishape/set_x/)(**float**) | ตั้งค่าพิกัด x ของมุมซ้ายบนของ shape หน่วยเป็น points. เขียน **float** |
| virtual void [set_Y](../ishape/set_y/)(**float**) | ตั้งค่าพิกัด y ของมุมซ้ายบนของ shape หน่วยเป็น points. เขียน **float** |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | อัพเดต geometry ของ shape จากอ็อบเจ็กต์ [IGeometryPath](../igeometrypath/). พิกัดต้องอ้างอิงจากมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) ให้เป็น [ShapeType::Custom](../shapetype/) |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | อัพเดต geometry ของ shape จากอาร์เรย์ของ [IGeometryPath](../igeometrypath/). พิกัดต้องอ้างอิงจากมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) ให้เป็น [ShapeType::Custom](../shapetype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า template argument ที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้เปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แบ่งร่วมกัน |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แบ่งร่วมกัน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับการอ้างอิงที่แบ่งร่วมกัน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการจำลองการสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentinel |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IPictureFrame](../ipictureframe/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)