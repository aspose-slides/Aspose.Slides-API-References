---
title: PictureFrame
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: แสดงกรอบที่มีรูปภาพอยู่ภายใน
type: docs
weight: 4733
url: /th/aspose.slides/pictureframe/
---
## PictureFrame คลาส

Represents a frame with a picture inside.

```cpp
class PictureFrame : public Aspose::Slides::GeometryShape,
                     public virtual Aspose::Slides::IPictureFrame
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่า property ของ placeholder ให้เป็นค่าที่ระบุ |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | สร้างและคืนค่าอาเรย์ขององค์ประกอบของ shape |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | คืนค่าการปรับของ shape ที่ตำแหน่ง index ที่ระบุ |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | คืนคอลเลกชันของค่าการปรับของ shape. อ่านได้อย่างเดียว [IAdjustValueCollection](../iadjustvaluecollection/) |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | คืนข้อความแทนที่เชื่อมโยงกับ shape. อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | คืนหัวข้อของข้อความแทนที่เชื่อมโยงกับ shape. อ่าน [System::String](../../system/string/) |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | คุณสมบัติเช่นระบุว่ารูปร่างจะเรนเดอร์อย่างไรในโหมดสีขาว-ดำ. อ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | คืนจำนวนจุดเชื่อมต่อบน shape. อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | คืนข้อมูลกำหนดเองของ shape. อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | คืนอ็อบเจกต์ [EffectFormat](../effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape. หมายเหตุ: อาจคืนค่า null สำหรับรูปแบบบางอย่างของ shape ที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | คืนอ็อบเจกต์ [FillFormat](../fillformat/) ที่มีคุณสมบัติการเติมสีสำหรับ shape. หมายเหตุ: อาจคืนค่า null สำหรับรูปแบบบางอย่างของ shape ที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | คืนคุณสมบัติของกรอบ shape. อ่าน [IShapeFrame](../ishapeframe/) |
| **float** [get_Height](../shape/get_height/)() override | รับความสูงของ shape วัดเป็นจุด. อ่าน **float** |
| **bool** [get_Hidden](../shape/get_hidden/)() override | ตรวจสอบว่า shape ถูกซ่อนหรือไม่. อ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | คืน hyperlink ที่กำหนดสำหรับการคลิกเมาส์. อ่าน [IHyperlink](../ihyperlink/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | คืนผู้จัดการ hyperlink. อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | คืน hyperlink ที่กำหนดสำหรับการเลื่อนเมาส์เหนือ. อ่าน [IHyperlink](../ihyperlink/) |
| **bool** [get_IsCameo](./get_iscameo/)() | ตรวจสอบว่า [PictureFrame](./) เป็นอ็อบเจกต์ Cameo หรือไม่. อ่านอย่างเดียว **bool** |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | ตรวจสอบว่า shape ถูกจัดกลุ่มหรือไม่. อ่านอย่างเดียว **bool** |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | ตรวจสอบว่า shape เป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | คืนอ็อบเจกต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape. หมายเหตุ: อาจคืนค่า null สำหรับรูปแบบบางอย่างของ shape ที่ไม่มีคุณสมบัติการจัดรูปแบบเส้น. อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | คืนชื่อของ shape. ต้องไม่เป็น null. ใช้ค่าสตริงว่างหากต้องการ. อ่าน [System::String](../../system/string/) |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | คืนรหัสประจำตัวที่ไม่ซ้ำกันระดับสไลด์ซึ่งคงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้จากทุกตำแหน่งในเอกสาร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_UniqueId](../shape/get_uniqueid/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | คืนอ็อบเจกต์ parent [GroupShape](../groupshape/) หาก shape ถูกจัดกลุ่ม. มิฉะนั้นคืน null. อ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](./get_pictureformat/)() override | คืนอ็อบเจกต์ [PictureFillFormat](../picturefillformat/) สำหรับ picture frame. อ่านอย่างเดียว [IPictureFillFormat](../ipicturefillformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](./get_pictureframelock/)() override | คืนล็อกของ shape. อ่านอย่างเดียว [IPictureFrameLock](../ipictureframelock/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | คืน placeholder สำหรับ shape. คืน null หาก shape ไม่มี placeholder. อ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | คืนการนำเสนอแม่ของสไลด์. อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | คืนคุณสมบัติ raw ของกรอบ shape. อ่าน [IShapeFrame](../ishapeframe/) |
| **float** [get_RelativeScaleHeight](./get_relativescaleheight/)() override | คืนสเกลความสูง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของ picture frame. ค่า 1.0 เท่ากับ 100%. อ่าน **float** |
| **float** [get_RelativeScaleWidth](./get_relativescalewidth/)() override | คืนสเกลความกว้าง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของ picture frame. ค่า 1.0 เท่ากับ 100%. อ่าน **float** |
| **float** [get_Rotation](../shape/get_rotation/)() override | คืนจำนวนองศาที่ shape ระบุถูกหมุนรอบแกน Z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | คืนล็อกของ shape. อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | คืนอ็อบเจกต์สไตล์ของ shape. อ่านอย่างเดียว [IShapeStyle](../ishapestyle/) |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | คืนสไลด์แม่ของ shape. อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | คืนอ็อบเจกต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติเอฟเฟกต์ 3D สำหรับ shape. หมายเหตุ: อาจคืนค่า null สำหรับรูปแบบบางอย่างของ shape ที่ไม่มีคุณสมบัติ 3D. อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | คืนรหัสภายในระดับการนำเสนอซึ่งออกแบบสำหรับใช้โดย add-ins หรือโค้ดอื่น ๆ. เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, ไม่ควรถือว่าเป็นคีย์ที่คงที่. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/) |
| **float** [get_Width](../shape/get_width/)() override | รับความกว้างของ shape วัดเป็นจุด. อ่าน **float** |
| **float** [get_X](../shape/get_x/)() override | รับค่าพิกัด x ของมุมบนซ้ายของ shape วัดเป็นจุด. อ่าน **float** |
| **float** [get_Y](../shape/get_y/)() override | รับค่าพิกัด y ของมุมบนซ้ายของ shape วัดเป็นจุด. อ่าน **float** |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | คืนตำแหน่งของ shape ในลำดับ z. Shapes[0] คืน shape ที่อยู่สุดท้ายของลำดับ z, และ Shapes[Count - 1] คืน shape ที่อยู่ตอนหน้า. อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | คืน shape placeholder พื้นฐาน (shape จากเลเอาท์และ/หรือสไลด์มาสเตอร์ที่ shape ปัจจุบันสืบทอดมาจาก) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | คืนสำเนาของเส้นทางของ geometry shape. พิกัดสัมพันธ์กับมุมซ้ายบนของ shape |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจกต์กำหนดเอง |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | คืน thumbnail ของ shape. ชนิด bounds ของ thumbnail shape [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ใช้เป็นค่าเริ่มต้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | คืน thumbnail ของ shape |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. Analogue ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | รับขอบเขตการแสดงผลของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. Analogue ของตัวดำเนินการ C# `is` |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคล cloning ของประเภทกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่า กับ nullptr ตามอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์โดยค่าที่ระบุ |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | กำหนดว่ารูปนี้ไม่ใช่ placeholder |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | ตั้งข้อความแทนที่เชื่อมโยงกับ shape. เขียน [System::String](../../system/string/) |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | ตั้งหัวข้อของข้อความแทนที่เชื่อมโยงกับ shape. เขียน [System::String](../../system/string/) |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | คุณสมบัติเช่นระบุว่ารูปร่างจะเรนเดอร์อย่างไรในโหมดสีขาว-ดำ. เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งคุณสมบัติของกรอบ shape. เขียน [IShapeFrame](../ishapeframe/) |
| void [set_Height](../shape/set_height/)(**float**) override | ตั้งความสูงของ shape วัดเป็นจุด. เขียน **float** |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | ตั้งค่าการซ่อนของ shape. เขียน **bool** |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้ง hyperlink ที่กำหนดสำหรับการคลิกเมาส์. เขียน [IHyperlink](../ihyperlink/) |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้ง hyperlink ที่กำหนดสำหรับการเลื่อนเมาส์เหนือ. เขียน [IHyperlink](../ihyperlink/) |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | ตั้งชื่อของ shape. ต้องไม่เป็น null. ใช้ค่าสตริงว่างหากต้องการ. เขียน [System::String](../../system/string/) |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งคุณสมบัติ raw ของกรอบ shape. เขียน [IShapeFrame](../ishapeframe/) |
| void [set_RelativeScaleHeight](./set_relativescaleheight/)(**float**) override | ตั้งสเกลความสูง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของ picture frame. ค่า 1.0 เท่ากับ 100%. เขียน **float** |
| void [set_RelativeScaleWidth](./set_relativescalewidth/)(**float**) override | ตั้งสเกลความกว้าง (สัมพันธ์กับขนาดรูปภาพต้นฉบับ) ของ picture frame. ค่า 1.0 เท่ากับ 100%. เขียน **float** |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | ตั้งจำนวนองศาที่ shape ระบุถูกหมุนรอบแกน Z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. เขียน **float** |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_Width](../shape/set_width/)(**float**) override | ตั้งความกว้างของ shape วัดเป็นจุด. เขียน **float** |
| void [set_X](../shape/set_x/)(**float**) override | ตั้งค่าพิกัด x ของมุมบนซ้ายของ shape วัดเป็นจุด. เขียน **float** |
| void [set_Y](../shape/set_y/)(**float**) override | ตั้งค่าพิกัด y ของมุมบนซ้ายของ shape วัดเป็นจุด. เขียน **float** |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | อัปเดต geometry ของ shape จากอ็อบเจกต์ [IGeometryPath](../igeometrypath/). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/) |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | อัปเดต geometry ของ shape จากอาเรย์ของ [IGeometryPath](../igeometrypath/). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้ง template argument ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่านับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue ของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์กำหนดเองเป็น string |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implement C# typeof([System.Object](../../system/object/)) construct |
| void [Unlock](../../system/object/unlock/)() | Implement C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentinel object |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหา [Shape](../shape/) เป็นไฟล์ SVG |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | บันทึกเนื้อหา [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## หมายเหตุ

The following examples shows how to change [Audio](../audio/) Frame Thumbnail. 
```cpp
auto presentation = System::MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);

// เพิ่ม audio frame ไปยังสไลด์ด้วยตำแหน่งและขนาดที่ระบุ.
auto audioStream = System::MakeObject<System::IO::FileStream>(u"sample2.mp3", System::IO::FileMode::Open, System::IO::FileAccess::Read);
auto audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(150.0f, 100.0f, 50.0f, 50.0f, audioStream);
audioStream->Dispose();

// เพิ่มรูปภาพไปยังทรัพยากรของการนำเสนอ.
auto imageStream = System::IO::File::OpenRead(u"eagle.jpeg");
auto audioImage = presentation->get_Images()->AddImage(imageStream);
imageStream->Dispose();

// ตั้งค่ารูปภาพสำหรับ audio frame.
audioFrame->get_PictureFormat()->get_Picture()->set_Image(audioImage);

//บันทึกการนำเสนอที่แก้ไขลงดิสก์
presentation->Save(u"example_out.pptx", SaveFormat::Pptx);
```

## ดูเพิ่มเติม

* คลาส [GeometryShape](../geometryshape/)
* คลาส [IPictureFrame](../ipictureframe/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)