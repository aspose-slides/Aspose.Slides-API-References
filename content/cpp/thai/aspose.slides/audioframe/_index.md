---
title: AudioFrame
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แสดงคลิปเสียงบนสไลด์.
type: docs
weight: 53
url: /th/aspose.slides/audioframe/
---
## AudioFrame คลาส

แสดงคลิปเสียงบนสไลด์.

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## Methods

| Method | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | เพิ่มตำแหน่งที่เก็บชั่วคราวใหม่หากไม่มีและตั้งค่าคุณสมบัติของตำแหน่งที่เก็บชั่วคราวให้เป็นค่าที่ระบุ |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | สร้างและคืนค่าอาร์เรย์ขององค์ประกอบของ shape |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ซึ่ง NaN สองค่านั้นถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# (double) ซึ่ง NaN สองค่านั้นถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | คืนค่าการปรับของ shape ที่ตำแหน่งที่กำหนด |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | คืนคอลเลกชันของค่าการปรับของ shape. อ่านอย่างเดียว [IAdjustValueCollection](../iadjustvaluecollection/) |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | คืนข้อความแทนที่เชื่อมกับ shape. อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | คืนชื่อเรื่องของข้อความแทนที่เชื่อมกับ shape. อ่าน [System::String](../../system/string/) |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | คืนค่าอินเด็กซ์ของแทร็กสุดท้าย อ่าน **int32_t** |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | คืนเวลาแทร็กสุดท้าย อ่าน **int32_t** |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | คืนค่าอินเด็กซ์ของแทร็กเริ่มต้น อ่าน **int32_t** |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | คืนเวลาแทร็กเริ่มต้น อ่าน **int32_t** |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | คุณสมบัติบ่งบอกว่า shape จะเรนเดอร์อย่างไรในโหมดแสดงผลสีดำ-ขาว. อ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | รับคอลเลกชันของคำบรรยายปิดที่เชื่อมกับ audio frame. คุณสมบัตินี้เป็นแบบอ่านอย่างเดียวและคืนค่า [ICaptionsCollection](../icaptionscollection/) ที่บรรจุติดแทร็กคำบรรยายทั้งหมด |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | คืนจำนวนจุดเชื่อมต่อบน shape. อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | คืนข้อมูลกำหนดเองของ shape. อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | คืนอ็อบเจกต์ [EffectFormat](../effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape. หมายเหตุ: อาจคืนค่า null สำหรับชนิด shape บางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| **bool** [get_Embedded](./get_embedded/)() override | ระบุว่าเสียงถูกฝังในงานนำเสนอหรือไม่. อ่านอย่างเดียว **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | คืนอ็อบเจกต์เสียงที่ฝังไว้. อ่าน [IAudio](../iaudio/) |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | ระบุระยะเวลา (มิลลิวินาที) ของการจางเข้าครั้งแรกของสื่อ. อ่าน **float** |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | ระบุระยะเวลา (มิลลิวินาที) ของการจางออกของสื่อ. อ่าน **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | คืนอ็อบเจกต์ [FillFormat](../fillformat/) ที่มีคุณสมบัติการเติมสีสำหรับ shape. หมายเหตุ: อาจคืนค่า null สำหรับชนิด shape บางประเภทที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | คืนคุณสมบัติของกรอบ shape. อ่าน [IShapeFrame](../ishapeframe/) |
| **float** [get_Height](../shape/get_height/)() override | รับความสูงของ shape หน่วยเป็นพ้อยต์. อ่าน **float** |
| **bool** [get_Hidden](../shape/get_hidden/)() override | ระบุว่า shape ถูกซ่อนหรือไม่. อ่าน **bool** |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | ระบุว่า [AudioFrame](./) ถูกซ่อนหรือไม่. อ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | คืน hyperlink ที่กำหนดสำหรับการคลิกเมาส์. อ่าน [IHyperlink](../ihyperlink/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | คืนผู้จัดการ hyperlink. อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | คืน hyperlink ที่กำหนดสำหรับการวางเมาส์. อ่าน [IHyperlink](../ihyperlink/) |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | ระบุว่า [PictureFrame](../pictureframe/) เป็นอ็อบเจกต์ Cameo หรือไม่. อ่านอย่างเดียว **bool** |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | ระบุว่า shape ถูกจัดกลุ่มหรือไม่. อ่านอย่างเดียว **bool** |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | ระบุว่า shape เป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | คืนอ็อบเจกต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติการจัดรูปเส้นสำหรับ shape. หมายเหตุ: อาจคืนค่า null สำหรับชนิด shape บางประเภทที่ไม่มีคุณสมบัติการจัดรูปเส้น. อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | คืนชื่อไฟล์เสียงที่เชื่อมกับ [AudioFrame](./). อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | คืนชื่อของ shape. ต้องไม่เป็น null. ใช้ค่าสตริงว่างหากจำเป็น. อ่าน [System::String](../../system/string/) |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | คืนตัวระบุที่ไม่ซ้ำกันระดับสไลด์ซึ่งคงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้จากที่ใดก็ได้ในเอกสาร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_UniqueId](../shape/get_uniqueid/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | คืนอ็อบเจกต์ [GroupShape](../groupshape/) พาเรนต์หาก shape ถูกจัดกลุ่ม. มิฉะนั้นคืน null. อ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | คืนอ็อบเจกต์ [PictureFillFormat](../picturefillformat/) สำหรับกรอบรูปภาพ. อ่านอย่างเดียว [IPictureFillFormat](../ipicturefillformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | คืนล็อกของ shape. อ่านอย่างเดียว [IPictureFrameLock](../ipictureframelock/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | คืนตำแหน่งที่เก็บชั่วคราวของ shape. คืน null หาก shape ไม่มีตำแหน่งที่เก็บชั่วคราว. อ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | ระบุว่าเสียงกำลังเล่นข้ามสไลด์หรือไม่. อ่าน **bool** |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | ระบุว่าเสียงถูกทำซ้ำหรือไม่. อ่าน **bool** |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | คืนโหมดการเล่นเสียง. อ่าน [AudioPlayModePreset](../audioplaymodepreset/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | คืนการนำเสนอพาเรนต์ของสไลด์. อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | คืนคุณสมบัติดิบของกรอบ shape. อ่าน [IShapeFrame](../ishapeframe/) |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | คืนอัตราส่วนความสูง (อิงจากขนาดภาพต้นฉบับ) ของกรอบภาพ. ค่า 1.0 แทน 100 %. อ่าน **float** |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | คืนอัตราส่วนความกว้าง (อิงจากขนาดภาพต้นฉบับ) ของกรอบภาพ. ค่า 1.0 แทน 100 %. อ่าน **float** |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | ระบุว่าเสียงจะถูกรีวินด์อัตโนมัติไปจุดเริ่มต้นหลังการเล่นหรือไม่. อ่าน **bool** |
| **float** [get_Rotation](../shape/get_rotation/)() override | คืนจำนวนองศาที่ shape หมุนรอบแกน z. ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | คืนล็อกของ shape. อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | คืนอ็อบเจกต์สไตล์ของ shape. อ่านอย่างเดียว [IShapeStyle](../ishapestyle/) |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | คืนสไลด์พาเรนต์ของ shape. อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | คืนอ็อบเจกต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติเอฟเฟกต์ 3d สำหรับ shape. หมายเหตุ: อาจคืนค่า null สำหรับชนิด shape บางประเภทที่ไม่มีคุณสมบัติ 3d. อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | ระบุระยะเวลา (มิลลิวินาที) ที่จะตัดออกจากส่วนท้ายของสื่อระหว่างการเล่น. อ่าน **float** |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | ระบุระยะเวลา (มิลลิวินาที) ที่จะตัดออกจากส่วนต้นของสื่อระหว่างการเล่น. อ่าน **float** |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | คืนตัวระบุภายในระดับการนำเสนอที่ออกแบบให้ใช้โดยส่วนเสริมหรือโค้ดอื่น ๆ. เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม จึงไม่ควรถือว่าเป็นคีย์ที่คงที่และไม่ซ้ำกัน. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/) |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | คืนระดับเสียงของออดิโอ. อ่าน [AudioVolumeMode](../audiovolumemode/) |
| **float** [get_VolumeValue](./get_volumevalue/)() override | คืนระดับเสียงของออดิโอเป็นเปอร์เซ็นต์. อ่าน **float** |
| **float** [get_Width](../shape/get_width/)() override | รับความกว้างของ shape หน่วยเป็นพ้อยต์. อ่าน **float** |
| **float** [get_X](../shape/get_x/)() override | รับพิกัด x ของมุมซ้ายบนของ shape หน่วยเป็นพ้อยต์. อ่าน **float** |
| **float** [get_Y](../shape/get_y/)() override | รับพิกัด y ของมุมซ้ายบนของ shape หน่วยเป็นพ้อยต์. อ่าน **float** |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | คืนตำแหน่งของ shape ในลำดับ z. Shapes[0] คืน shape ที่อยู่ด้านหลังสุดของลำดับ z, และ Shapes[Shapes.Count - 1] คืน shape ที่อยู่ด้านหน้าสุดของลำดับ z. อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | คืน shape placeholder พื้นฐาน (shape จากเลย์เอาต์และ/หรือสไลด์หลักที่ shape ปัจจุบันสืบทอดมาจาก) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมกับอ็อบเจกต์ |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | คืนสำเนาเส้นทางของ shape เรขาคณิต. พิกัดอ้างอิงจากมุมซ้ายบนของ shape |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เหมือนเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการสร้างแฮชของอ็อบเจกต์กำหนดเอง |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | คืนรูปย่อของ shape. ชนิดขอบเขตรูปย่อ [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ถูกใช้โดยค่าเริ่มต้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | คืนรูปย่อของ shape |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เหมือนการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | รับขอบเขตการแสดงผลของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่ระบุโดย targetType. คล้ายกับตัวดำเนินการ C# `is` |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เหมือนเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดการสำเนาคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดการสำเนาคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดค่าเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดค่าเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | กำหนดว่า shape นี้ไม่ใช่ placeholder |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | ตั้งข้อความแทนที่เชื่อมกับ shape. เขียน [System::String](../../system/string/) |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | ตั้งชื่อเรื่องของข้อความแทนที่เชื่อมกับ shape. เขียน [System::String](../../system/string/) |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | ตั้งค่าอินเด็กซ์ของแทร็กสุดท้าย เขียน **int32_t** |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | ตั้งค่าเวลาแทร็กสุดท้าย. เขียน **int32_t** |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | ตั้งค่าอินเด็กซ์ของแทร็กเริ่มต้น. เขียน **int32_t** |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | ตั้งค่าเวลาแทร็กเริ่มต้น. เขียน **int32_t** |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | คุณสมบัติบ่งบอกว่า shape จะเรนเดอร์อย่างไรในโหมดแสดงผลสีดำ-ขาว. เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | ตั้งอ็อบเจกต์เสียงที่ฝังไว้. เขียน [IAudio](../iaudio/) |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | ระบุระยะเวลา (มิลลิวินาที) ของการจางเข้าครั้งแรกของสื่อ. เขียน **float** |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | ระบุระยะเวลา (มิลลิวินาที) ของการจางออกของสื่อ. เขียน **float** |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งคุณสมบัติของกรอบ shape. เขียน [IShapeFrame](../ishapeframe/) |
| void [set_Height](../shape/set_height/)(**float**) override | ตั้งความสูงของ shape หน่วยเป็นพ้อยต์. เขียน **float** |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | ระบุว่า shape ถูกซ่อนหรือไม่. เขียน **bool** |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | ระบุว่า [AudioFrame](./) ถูกซ่อนหรือไม่. เขียน **bool** |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้ง hyperlink ที่กำหนดสำหรับการคลิกเมาส์. เขียน [IHyperlink](../ihyperlink/) |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้ง hyperlink ที่กำหนดสำหรับการวางเมาส์. เขียน [IHyperlink](../ihyperlink/) |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | กำหนดตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | ตั้งชื่อไฟล์เสียงที่เชื่อมกับ [AudioFrame](./). เขียน [System::String](../../system/string/) |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | ตั้งชื่อของ shape. ต้องไม่เป็น null. ใช้ค่าสตริงว่างหากจำเป็น. เขียน [System::String](../../system/string/) |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | ระบุว่าเสียงกำลังเล่นข้ามสไลด์หรือไม่. เขียน **bool** |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | ระบุว่าเสียงทำซ้ำหรือไม่. เขียน **bool** |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | ตั้งโหมดการเล่นเสียง. เขียน [AudioPlayModePreset](../audioplaymodepreset/) |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งคุณสมบัติดิบของกรอบ shape. เขียน [IShapeFrame](../ishapeframe/) |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | ตั้งอัตราส่วนความสูง (อิงจากขนาดภาพต้นฉบับ) ของกรอบภาพ. ค่า 1.0 แทน 100 %. เขียน **float** |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | ตั้งอัตราส่วนความกว้าง (อิงจากขนาดภาพต้นฉบับ) ของกรอบภาพ. ค่า 1.0 แทน 100 %. เขียน **float** |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | ระบุว่าเสียงจะถูกรีวินด์อัตโนมัติไปจุดเริ่มต้นหลังการเล่นหรือไม่. เขียน **bool** |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | ตั้งจำนวนองศาที่ shape หมุนรอบแกน z. ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนา� clocks. เขียน **float** |
| void [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | ระบุระยะเวลา (มิลลิวินาที) ที่จะตัดออกจากส่วนท้ายของสื่อระหว่างการเล่น. เขียน **float** |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | ระบุระยะเวลา (มิลลิวินาที) ที่จะตัดออกจากส่วนต้นของสื่อระหว่างการเล่น. เขียน **float** |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | ตั้งระดับเสียง. เขียน [AudioVolumeMode](../audiovolumemode/) |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | ตั้งระดับเสียงเป็นเปอร์เซ็นต์. เขียน **float** |
| void [set_Width](../shape/set_width/)(**float**) override | ตั้งความกว้างของ shape หน่วยเป็นพ้อยต์. เขียน **float** |
| void [set_X](../shape/set_x/)(**float**) override | ตั้งพิกัด x ของมุมซ้ายบนของ shape หน่วยเป็นพ้อยต์. เขียน **float** |
| void [set_Y](../shape/set_y/)(**float**) override | ตั้งพิกัด y ของมุมซ้ายบนของ shape หน่วยเป็นพ้อยต์. เขียน **float** |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | ปรับรูปทรงของ shape จากอ็อบเจกต์ [IGeometryPath](../igeometrypath/). พิกัดต้องอ้างอิงจากมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/) |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | ปรับรูปทรงของ shape จากอาร์เรย์ของ [IGeometryPath](../igeometrypath/). พิกัดต้องอ้างอิงจากมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เหมือนเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามคอนสตรัคต์ C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# ปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหา [Shape](../shape/) เป็นไฟล์ SVG |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | บันทึกเนื้อหา [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## หมายเหตุ

ตัวอย่างต่อไปนี้แสดงวิธีการเปลี่ยนแปลงตัวเลือกการเล่นของ [Audio](../audio/).

```cpp
auto pres = System::MakeObject<Presentation>(u"AudioFrameEmbed_out.pptx");

// Gets the AudioFrame shape
System::SharedPtr<AudioFrame> audioFrame = System::ExplicitCast<AudioFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// Sets the Play mode to play on click
audioFrame->set_PlayMode(AudioPlayModePreset::OnClick);
// Sets the volume to Low
audioFrame->set_Volume(AudioVolumeMode::Low);
// Sets the audio to play across slides
audioFrame->set_PlayAcrossSlides(true);
// Disables loop for the audio
audioFrame->set_PlayLoopMode(false);
// Hides the AudioFrame during the slide show
audioFrame->set_HideAtShowing(true);
// Rewinds the audio to start after playing
audioFrame->set_RewindAudio(true);
// Saves the PowerPoint file to disk
pres->Save(u"AudioFrameEmbed_changed.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* Class [PictureFrame](../pictureframe/)
* Class [IAudioFrame](../iaudioframe/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)