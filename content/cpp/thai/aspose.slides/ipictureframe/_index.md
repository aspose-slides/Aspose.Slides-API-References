---
title: IPictureFrame
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงกรอบที่มีรูปภาพอยู่ภายใน.
type: docs
weight: 3251
url: /th/aspose.slides/ipictureframe/
---
## IPictureFrame คลาส

แสดงกรอบที่มีรูปภาพอยู่ภายใน.

```cpp
class IPictureFrame : public virtual Aspose::Slides::IGeometryShape
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder เป็นค่าที่ระบุ |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | สร้างและคืนค่าอาเรย์ขององค์ประกอบใน shape |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับการทำงานภายในเท่านั้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | คืนค่าการปรับปรุงของ shape ที่ตำแหน่งที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | คืนชุดของการปรับปรุงของ shape. แบบอ่านอย่างเดียว [IAdjustValueCollection](../iadjustvaluecollection/) |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | คืนข้อความแทนที่เชื่อมกับ shape. อ่าน [System::String](../../system/string/) |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | คืนหัวข้อของข้อความแทนที่เชื่อมกับ shape. อ่าน [System::String](../../system/string/) |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | คุณสมบัตินี้ระบุว่า shape จะถูกแสดงผลในโหมดสีขาว-ดำอย่างไร. อ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | คืนจำนวนจุดเชื่อมต่อบน shape. แบบอ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | คืนข้อมูลกำหนดเองของ shape. แบบอ่านอย่างเดียว [ICustomData](../icustomdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | คืนอ็อบเจ็กต์ [EffectFormat](../effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape. แบบอ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | คืนอ็อบเจ็กต์ [FillFormat](../fillformat/) ที่มีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับ shape. แบบอ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | คืนคุณสมบัติของเฟรม shape. อ่าน [IShapeFrame](../ishapeframe/) |
| virtual **float** [get_Height](../ishape/get_height/)() | รับความสูงของ shape หน่วยเป็นจุด. อ่าน **float** |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | กำหนดว่า shape ซ่อนอยู่หรือไม่. อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | คืน hyperlink ที่กำหนดสำหรับคลิกเมาส์. อ่าน [IHyperlink](../ihyperlink/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ตัวจัดการ Hyperlink แบบอ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | คืน hyperlink ที่กำหนดสำหรับเมาส์เหนือ. อ่าน [IHyperlink](../ihyperlink/) |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | กำหนดว่า shape อยู่ในกลุ่มหรือไม่. แบบอ่านอย่างเดียว **bool** |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | กำหนดว่า shape เป็น TextHolder หรือไม่. แบบอ่านอย่างเดียว **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | คืนอ็อบเจ็กต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape. แบบอ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | คืนชื่อของ shape. อ่าน [System::String](../../system/string/) |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | คืนตัวระบุที่ไม่ซ้ำกันระดับสไลด์ ซึ่งคงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้จากทุกที่ในเอกสาร. แบบอ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_UniqueId](../ishape/get_uniqueid/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | คืนอ็อบเจ็กต์พาเรนท์ [GroupShape](../groupshape/) หาก shape อยู่ในกลุ่ม. หากไม่ใช่จะคืนค่า null. แบบอ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](./get_pictureformat/)() | คืนอ็อบเจ็กต์ [PictureFillFormat](../picturefillformat/) สำหรับ picture frame. แบบอ่านอย่างเดียว [IPictureFillFormat](../ipicturefillformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](./get_pictureframelock/)() | คืนล็อกของ [PictureFrame](../pictureframe/). แบบอ่านอย่างเดียว [IPictureFrameLock](../ipictureframelock/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | คืน placeholder ของ shape. แบบอ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | คืนการนำเสนอ. แบบอ่านอย่างเดียว [IPresentation](../ipresentation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | คืนคุณสมบัติของเฟรม shape ดิบ. อ่าน [IShapeFrame](../ishapeframe/) |
| virtual **float** [get_RelativeScaleHeight](./get_relativescaleheight/)() | คืนสเกลความสูง (เทียบกับขนาดภาพต้นฉบับ) ของ picture frame. ค่า 1.0 เท่ากับ 100%. อ่าน **float** |
| virtual **float** [get_RelativeScaleWidth](./get_relativescalewidth/)() | คืนสเกลความกว้าง (เทียบกับขนาดภาพต้นฉบับ) ของ picture frame. ค่า 1.0 เท่ากับ 100%. อ่าน **float** |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | คืนจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | คืนล็อกของ shape. แบบอ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | คืนอ็อบเจ็กต์สไตล์ของ shape. แบบอ่านอย่างเดียว [IShapeStyle](../ishapestyle/) |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | คืนประเภท geometry preset. หมายเหตุ: เมื่อค่าถูกเปลี่ยนค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าตั้งต้น. อ่าน [Slides::ShapeType](../shapetype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | คืนสไลด์ฐาน. แบบอ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | คืนอ็อบเจ็กต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape. แบบอ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | คืนตัวระบุภายในระดับการนำเสนอซึ่งตั้งใจให้ใช้โดย add-in หรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม จึงต้องไม่ถือว่าเป็นคีย์ที่คงที่. แบบอ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/) |
| virtual **float** [get_Width](../ishape/get_width/)() | รับความกว้างของ shape หน่วยเป็นจุด. อ่าน **float** |
| virtual **float** [get_X](../ishape/get_x/)() | รับพิกัด x ของมุมบนซ้ายของ shape หน่วยเป็นจุด. อ่าน **float** |
| virtual **float** [get_Y](../ishape/get_y/)() | รับพิกัด y ของมุมบนซ้ายของ shape หน่วยเป็นจุด. อ่าน **float** |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | คืนตำแหน่งของ shape ในลำดับ z. Shapes[0] คืน shape ที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืน shape ที่อยู่หน้าสุดของลำดับ z. แบบอ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | คืน shape placeholder พื้นฐาน (shape จาก layout หรือ master slide ที่ shape ปัจจุบันสืบทอดมาจาก) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมกับอ็อบเจ็กต์ |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | คืนสำเนาของเส้นทางของ geometry shape. พิกัดอ้างอิงจากมุมซ้ายบนของ shape |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถทำแฮชของอ็อบเจ็กต์กำหนดเองได้ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | คืน thumbnail ของ shape. ประเภทขอบของ shape thumbnail [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ถูกใช้เป็นค่าเริ่มต้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | คืน thumbnail ของ shape |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่ targetType ระบุหรือไม่. เทียบเคียงกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ใช้งานคำสั่ง lock() ของ C# เพื่อทำการล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถคล cloning ของประเภทกำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างคัดลอกของคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า. จริง ๆ ไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างคัดลอกของคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมตามค่าที่ระบุ |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | กำหนดว่า shape นี้ไม่ใช่ placeholder |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | ตั้งข้อความแทนที่เชื่อมกับ shape. เขียน [System::String](../../system/string/) |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งหัวข้อของข้อความแทนที่เชื่อมกับ shape. เขียน [System::String](../../system/string/) |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | คุณสมบัตินี้ระบุว่า shape จะถูกแสดงผลในโหมดสีขาว-ดำอย่างไร. เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของเฟรม shape. เขียน [IShapeFrame](../ishapeframe/) |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ตั้งความสูงของ shape หน่วยเป็นจุด. เขียน **float** |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | กำหนดว่า shape ซ่อนอยู่หรือไม่. เขียน **bool** |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้ง hyperlink ที่กำหนดสำหรับคลิกเมาส์. เขียน [IHyperlink](../ihyperlink/) |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้ง hyperlink ที่กำหนดสำหรับเมาส์เหนือ. เขียน [IHyperlink](../ihyperlink/) |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ตั้งตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | ตั้งชื่อของ shape. เขียน [System::String](../../system/string/) |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งคุณสมบัติของเฟรม shape ดิบ. เขียน [IShapeFrame](../ishapeframe/) |
| virtual void [set_RelativeScaleHeight](./set_relativescaleheight/)(**float**) | ตั้งสเกลความสูง (เทียบกับขนาดภาพต้นฉบับ) ของ picture frame. ค่า 1.0 เท่ากับ 100%. เขียน **float** |
| virtual void [set_RelativeScaleWidth](./set_relativescalewidth/)(**float**) | ตั้งสเกลความกว้าง (เทียบกับขนาดภาพต้นฉบับ) ของ picture frame. ค่า 1.0 เท่ากับ 100%. เขียน **float** |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | ตั้งจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. เขียน **float** |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | ตั้งประเภท geometry preset. หมายเหตุ: เมื่อค่าเปลี่ยนแปลงค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าตั้งต้น. เขียน [Slides::ShapeType](../shapetype/) |
| virtual void [set_Width](../ishape/set_width/)(**float**) | ตั้งความกว้างของ shape หน่วยเป็นจุด. เขียน **float** |
| virtual void [set_X](../ishape/set_x/)(**float**) | ตั้งพิกัด x ของมุมบนซ้ายของ shape หน่วยเป็นจุด. เขียน **float** |
| virtual void [set_Y](../ishape/set_y/)(**float**) | ตั้งพิกัด y ของมุมบนซ้ายของ shape หน่วยเป็นจุด. เขียน **float** |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | อัปเดต geometry ของ shape จากอ็อบเจ็กต์ [IGeometryPath](../igeometrypath/). พิกัดต้องอ้างอิงจากมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) ไปเป็น [ShapeType::Custom](../shapetype/) |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | อัปเดต geometry ของ shape จากอาร์เรย์ของ [IGeometryPath](../igeometrypath/). พิกัดต้องอ้างอิงจากมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) ไปเป็น [ShapeType::Custom](../shapetype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เท็มเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงร่วม. ควรไม่เรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม. ควรไม่เรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้แปลงอ็อบเจ็กต์กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ใช้งานโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ใช้งานคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak. ควรไม่เรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak. ควรไม่เรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IGeometryShape](../igeometryshape/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)