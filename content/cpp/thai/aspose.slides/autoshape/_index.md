---
title: AutoShape
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึง AutoShape.
type: docs
weight: 66
url: /th/aspose.slides/autoshape/
---
## คลาส AutoShape

แสดงถึง [AutoShape](./).

```cpp
class AutoShape : public Aspose::Slides::GeometryShape,
                  public Aspose::Slides::IAutoShape
```

## Methods

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [AddTextFrame](./addtextframe/)([System::String](../../system/string/)) override | เพิ่ม [TextFrame](../textframe/) ใหม่ให้กับ shape หาก shape มี [TextFrame](../textframe/) อยู่แล้วก็จะเปลี่ยนข้อความของมันเท่านั้น |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | สร้างและคืนค่าอาร์เรย์ขององค์ประกอบของ shape |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในรูปแบบของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในรูปแบบของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อใช้ภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | คืนค่าการปรับของ shape ที่ดัชนีที่ระบุ |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | คืนค่าชุดของค่าการปรับของ shape. อ่านอย่างเดียว [IAdjustValueCollection](../iadjustvaluecollection/) |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | คืนค่าข้อความทางเลือกที่เชื่อมโยงกับ shape. อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | คืนค่าชื่อเรื่องของข้อความทางเลือกที่เชื่อมโยงกับ shape. อ่าน [System::String](../../system/string/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IAutoShapeLock](../iautoshapelock/)\> [get_AutoShapeLock](./get_autoshapelock/)() override | คืนค่าการล็อคของ autoshape. อ่านอย่างเดียว [IAutoShapeLock](../iautoshapelock/) |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | คุณสมบัติระบุว่ารูปจะเรนเดอร์อย่างไรในโหมดสีขาวดำ. อ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | คืนค่าจำนวนจุดเชื่อมต่อบน shape. อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | คืนค่าข้อมูลแบบกำหนดเองของ shape. อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | คืนค่าอ็อบเจกต์ [EffectFormat](../effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape. หมายเหตุ: อาจคืนค่า null สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | คืนค่าอ็อบเจกต์ [FillFormat](../fillformat/) ที่มีคุณสมบัติการจัดรูปแบบเติมสีสำหรับ shape. หมายเหตุ: อาจคืนค่า null สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | คืนค่าคุณสมบัติของเฟรม shape. อ่าน [IShapeFrame](../ishapeframe/) |
| **float** [get_Height](../shape/get_height/)() override | รับความสูงของ shape, วัดเป็นจุด. อ่าน **float** |
| **bool** [get_Hidden](../shape/get_hidden/)() override | กำหนดว่ารูปซ่อนอยู่หรือไม่. อ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | คืนค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน [IHyperlink](../ihyperlink/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | คืนค่าตัวจัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | คืนค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับเมาส์ชี้อยู่. อ่าน [IHyperlink](../ihyperlink/) |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | รับตัวเลือก 'Mark as decorative' ตัวเลือก อ่าน/เขียน **bool** |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | กำหนดว่ารูปเป็นกลุ่มหรือไม่. อ่านอย่างเดียว **bool** |
| **bool** [get_IsTextBox](./get_istextbox/)() override | ระบุว่ารูปเป็นกล่องข้อความหรือไม่ |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | กำหนดว่ารูปเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | คืนค่าอ็อบเจกต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape. หมายเหตุ: อาจคืนค่า null สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | คืนชื่อของ shape. ต้องไม่เป็นค่า null. ใช้ค่าว่างหากจำเป็น. อ่าน [System::String](../../system/string/) |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | คืนค่าเอกลักษณ์ที่ไม่ซ้ำกันเฉพาะสไลด์ที่คงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop อ้างอิง shape ได้อย่างเชื่อถือจากที่ใดในเอกสารก็ได้. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_UniqueId](../shape/get_uniqueid/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | คืนอ็อบเจกต์ [GroupShape](../groupshape/) พ่อแม่หาก shape อยู่ในกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | คืน placeholder สำหรับ shape. คืนค่า null หาก shape ไม่มี placeholder. อ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | คืนการนำเสนอแม่ของสไลด์. อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | คืนคุณสมบัติของเฟรม shape ดิบ. อ่าน [IShapeFrame](../ishapeframe/) |
| **float** [get_Rotation](../shape/get_rotation/)() override | คืนค่ามากกว่าหน่วยองศาที่ shape ระบุหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | คืนค่าการล็อคของ shape. อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | คืนอ็อบเจกต์สไตล์ของ shape. อ่านอย่างเดียว [IShapeStyle](../ishapestyle/) |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../geometryshape/get_shapetype/)() override | คืนประเภทพรีเซ็ตของเรขาคณิต. หมายเหตุ: เมื่อค่าเปลี่ยนทุกค่าการปรับจะรีเซ็ตเป็นค่าเริ่มต้น. อ่าน [Slides::ShapeType](../shapetype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | คืนสไลด์แม่ของ shape. อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_TextFrame](./get_textframe/)() override | คืนอ็อบเจกต์ [TextFrame](../textframe/) สำหรับ [AutoShape](./). อ่านอย่างเดียว [ITextFrame](../itextframe/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | คืนอ็อบเจกต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติเอฟเฟกต์ 3d สำหรับ shape. หมายเหตุ: อาจคืนค่า null สำหรับบางประเภทของ shape ที่ไม่มีคุณสมบัติ 3d. อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | คืนตัวระบุภายในระดับการนำเสนอที่ออกแบบเพื่อใช้โดย add-in หรือโค้ดอื่น. เนื่องจากค่าที่นี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม จึงไม่ควรถือเป็นคีย์ที่ไม่ซ้ำกันถาวร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/) |
| **bool** [get_UseBackgroundFill](./get_usebackgroundfill/)() override | กำหนดว่ารูปนี้ควรเติมด้วยพื้นหลังของสไลด์แทนที่สไตล์หรือรูปแบบการเติมหรือไม่. อ่าน **bool** |
| **float** [get_Width](../shape/get_width/)() override | รับความกว้างของ shape, วัดเป็นจุด. อ่าน **float** |
| **float** [get_X](../shape/get_x/)() override | รับค่าพิกัด x ของมุมซ้ายบนของ shape, วัดเป็นจุด. อ่าน **float** |
| **float** [get_Y](../shape/get_y/)() override | รับค่าพิกัด y ของมุมซ้ายบนของ shape, วัดเป็นจุด. อ่าน **float** |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | คืนตำแหน่งของ shape ในลำดับ z. Shapes[0] คืน shape ที่อยู่ด้านหลังสุดของลำดับ z, และ Shapes[Shapes.Count - 1] คืน shape ที่อยู่ด้านหน้าสุดของลำดับ z. อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | คืน shape placeholder พื้นฐาน (shape จากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่ shape ปัจจุบันสืบทอดมาจาก) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | คืนสำเนาเส้นทางของรูปเรขาคณิต. พิกัดสัมพันธ์กับมุมซ้ายบนของ shape |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | วิเคราะห์ของ C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจกต์ที่กำหนดเอง |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | คืน thumbnail ของ shape. รูปแบบ bounds ของ thumbnail shape [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ใช้เป็นค่าเริ่มต้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | คืน thumbnail ของ shape |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. วิเคราะห์ของ C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | รับขอบเขตภาพของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. วิเคราะห์ของ C# 'is' |
| void [Lock](../../system/object/lock/)() | Implement C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | วิเคราะห์ของ C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | อ้างอิงเปรียบเทียบอ็อบเจกต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมตามค่าที่ระบุ |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | กำหนดว่ารูปนี้ไม่ใช่ placeholder |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | ตั้งค่าข้อความทางเลือกที่เชื่อมโยงกับ shape. เขียน [System::String](../../system/string/) |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | ตั้งค่าชื่อเรื่องของข้อความทางเลือกที่เชื่อมโยงกับ shape. เขียน [System::String](../../system/string/) |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | คุณสมบัติระบุว่ารูปจะเรนเดอร์อย่างไรในโหมดสีขาวดำ. เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของเฟรม shape. เขียน [IShapeFrame](../ishapeframe/) |
| void [set_Height](../shape/set_height/)(**float**) override | ตั้งค่าความสูงของ shape, วัดเป็นจุด. เขียน **float** |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | กำหนดว่ารูปซ่อนอยู่หรือไม่. เขียน **bool** |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. เขียน [IHyperlink](../ihyperlink/) |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับเมาส์ชี้อยู่. เขียน [IHyperlink](../ihyperlink/) |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | ตั้งค่าชื่อของ shape. ต้องไม่เป็นค่า null. ใช้ค่าว่างหากจำเป็น. เขียน [System::String](../../system/string/) |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของเฟรม shape ดิบ. เขียน [IShapeFrame](../ishapeframe/) |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | ตั้งค่ามากกว่าหน่วยองศาที่ shape ระบุหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. เขียน **float** |
| void [set_ShapeType](../geometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override | ตั้งค่าประเภทพรีเซ็ตของเรขาคณิต. หมายเหตุ: เมื่อค่าเปลี่ยนทุกค่าการปรับจะรีเซ็ตเป็นค่าเริ่มต้น. เขียน [Slides::ShapeType](../shapetype/) |
| void [set_UseBackgroundFill](./set_usebackgroundfill/)(**bool**) override | กำหนดว่ารูปนี้ควรเติมด้วยพื้นหลังของสไลด์แทนที่สไตล์หรือรูปแบบการเติมหรือไม่. เขียน **bool** |
| void [set_Width](../shape/set_width/)(**float**) override | ตั้งค่าความกว้างของ shape, วัดเป็นจุด. เขียน **float** |
| void [set_X](../shape/set_x/)(**float**) override | ตั้งค่าค่าพิกัด x ของมุมซ้ายบนของ shape, วัดเป็นจุด. เขียน **float** |
| void [set_Y](../shape/set_y/)(**float**) override | ตั้งค่าค่าพิกัด y ของมุมซ้ายบนของ shape, วัดเป็นจุด. เขียน **float** |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | อัปเดตรูปเรขาคณิตของ shape จากอ็อบเจกต์ [IGeometryPath](../igeometrypath/). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/) |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | อัปเดตรูปเรขาคณิตของ shape จากอาร์เรย์ของ [IGeometryPath](../igeometrypath/). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนท์เทมเพลตที่ n เป็น weak pointer (แทน shared). อนุญาตสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | วิเคราะห์ของ C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implement C# typeof([System.Object](../../system/object/)) construct |
| void [Unlock](../../system/object/unlock/)() | Implement C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิง weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## ดูเพิ่มเติม

* คลาส [GeometryShape](../geometryshape/)
* คลาส [IAutoShape](../iautoshape/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)