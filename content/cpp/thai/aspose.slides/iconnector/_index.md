---
title: IConnector
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนของตัวเชื่อม.
type: docs
weight: 1847
url: /th/aspose.slides/iconnector/
---
## IConnector คลาส

Represents a connector.

```cpp
class IConnector : public virtual Aspose::Slides::IGeometryShape
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | สร้างและส่งกลับอาเรย์ขององค์ประกอบของ shape |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบแบบ floating point ของ C# ที่ถือว่า NaN สองค่ามีค่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบแบบ floating point ของ C# ที่ถือว่า NaN สองค่ามีค่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุภายในเท่านั้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | ส่งกลับค่าการปรับของ shape ณ ดัชนีที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | ส่งกลับคอลเลกชันของค่าการปรับของ shape (อ่าน-อย่างเดียว) [IAdjustValueCollection](../iadjustvaluecollection/) |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | ส่งกลับข้อความอธิบายทางเลือกที่เชื่อมโยงกับ shape (อ่าน-อย่างเดียว) [System::String](../../system/string/) |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | ส่งกลับชื่อเรื่องของข้อความอธิบายทางเลือกที่เชื่อมโยงกับ shape (อ่าน-อย่างเดียว) [System::String](../../system/string/) |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | คุณสมบัติกำหนดว่า shape จะถูกแสดงผลในโหมดขาว-ดำอย่างไร (อ่าน-อย่างเดียว) [Slides::BlackWhiteMode](../blackwhitemode/) |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | ส่งกลับจำนวนจุดเชื่อมต่อบน shape (อ่าน-อย่างเดียว) **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IConnectorLock](../iconnectorlock/)\> [get_ConnectorLock](./get_connectorlock/)() | ส่งกลับล็อคของ [Connector](../connector/) (อ่าน-อย่างเดียว) [IConnectorLock](../iconnectorlock/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | ส่งกลับข้อมูลกำหนดเองของ shape (อ่าน-อย่างเดียว) [ICustomData](../icustomdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | ส่งกลับอ็อบเจ็กต์ [EffectFormat](../effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape (อ่าน-อย่างเดียว) [IEffectFormat](../ieffectformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_EndShapeConnectedTo](./get_endshapeconnectedto/)() | ส่งกลับ shape ที่เชื่อมต่อกับปลายของ connector (อ่าน-อย่างเดียว) [IShape](../ishape/) |
| virtual **uint32_t** [get_EndShapeConnectionSiteIndex](./get_endshapeconnectionsiteindex/)() | ส่งกลับดัชนีของจุดเชื่อมต่อสำหรับ shape ปลาย (อ่าน-อย่างเดียว) **uint32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | ส่งกลับอ็อบเจ็กต์ [FillFormat](../fillformat/) ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับ shape (อ่าน-อย่างเดียว) [IFillFormat](../ifillformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | ส่งกลับคุณสมบัติของเฟรม shape (อ่าน-อย่างเดียว) [IShapeFrame](../ishapeframe/) |
| virtual **float** [get_Height](../ishape/get_height/)() | รับความสูงของ shape หน่วยเป็นจุด (อ่าน-อย่างเดียว) **float** |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | ตรวจสอบว่า shape ถูกซ่อนอยู่หรือไม่ (อ่าน-อย่างเดียว) **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | ส่งกลับ hyperlink ที่กำหนดสำหรับการคลิกเมาส์ (อ่าน-อย่างเดียว) [IHyperlink](../ihyperlink/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ตัวจัดการ hyperlink (อ่าน-อย่างเดียว) [IHyperlinkManager](../ihyperlinkmanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | ส่งกลับ hyperlink ที่กำหนดสำหรับการวางเมาส์ (อ่าน-อย่างเดียว) [IHyperlink](../ihyperlink/) |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | รับตัวเลือก 'Mark as decorative' (อ่าน-เขียน) **bool** |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | ตรวจสอบว่า shape ถูกจัดกลุ่มหรือไม่ (อ่าน-อย่างเดียว) **bool** |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | ตรวจสอบว่า shape เป็น TextHolder หรือไม่ (อ่าน-อย่างเดียว) **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | ส่งกลับอ็อบเจ็กต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape (อ่าน-อย่างเดียว) [ILineFormat](../ilineformat/) |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | ส่งกลับชื่อของ shape (อ่าน-อย่างเดียว) [System::String](../../system/string/) |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | ส่งกลับรหัสประจำสไลด์ที่คงที่ตลอดอายุของ shape และใช้ในการอ้างอิง shape จากที่ใดก็ได้ในเอกสาร (อ่าน-อย่างเดียว) **uint32_t** ดูเพิ่มเติม [IShape::get_UniqueId](../ishape/get_uniqueid/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | ส่งกลับอ็อบเจ็กต์ [GroupShape](../groupshape/) พ่อแม่หาก shape ถูกจัดกลุ่ม มิฉะนั้นส่งกลับ null (อ่าน-อย่างเดียว) [IGroupShape](../igroupshape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | ส่งกลับ placeholder ของ shape (อ่าน-อย่างเดียว) [IPlaceholder](../iplaceholder/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | ส่งกลับงานนำเสนอ (อ่าน-อย่างเดียว) [IPresentation](../ipresentation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | ส่งกลับคุณสมบัติของเฟรม shape ดิบ (อ่าน-อย่างเดียว) [IShapeFrame](../ishapeframe/) |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | ส่งกลับจำนวนองศาที่ shape ถูกหมุนรอบแกน Z (ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา, ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา) (อ่าน-อย่างเดียว) **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | ส่งกลับล็อคของ shape (อ่าน-อย่างเดียว) [IBaseShapeLock](../ibaseshapelock/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | ส่งกลับอ็อบเจ็กต์ style ของ shape (อ่าน-อย่างเดียว) [IShapeStyle](../ishapestyle/) |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | ส่งกลับประเภท preset ของเรขาคณิต (หมายเหตุ: การเปลี่ยนค่าจะทำให้ค่าการปรับทั้งหมดรีเซ็ตเป็นค่าเริ่มต้น) (อ่าน-อย่างเดียว) [Slides::ShapeType](../shapetype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | ส่งกลับสไลด์ฐาน (อ่าน-อย่างเดียว) [IBaseSlide](../ibaseslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_StartShapeConnectedTo](./get_startshapeconnectedto/)() | ส่งกลับ shape ที่เชื่อมต่อกับจุดเริ่มต้นของ connector (อ่าน-อย่างเดียว) [IShape](../ishape/) |
| virtual **uint32_t** [get_StartShapeConnectionSiteIndex](./get_startshapeconnectionsiteindex/)() | ส่งกลับดัชนีของจุดเชื่อมต่อสำหรับ shape เริ่มต้น (อ่าน-อย่างเดียว) **uint32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | ส่งกลับอ็อบเจ็กต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape (อ่าน-อย่างเดียว) [IThreeDFormat](../ithreedformat/) |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | ส่งกลับรหัสภายในระดับงานนำเสนอที่ใช้โดย add-in หรือโค้ดอื่น ๆ (ไม่ควรใช้เป็นคีย์ที่คงที่) (อ่าน-อย่างเดียว) **uint32_t** ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/) |
| virtual **float** [get_Width](../ishape/get_width/)() | รับความกว้างของ shape หน่วยเป็นจุด (อ่าน-อย่างเดียว) **float** |
| virtual **float** [get_X](../ishape/get_x/)() | รับพิกัด x ของมุมซ้ายบนของ shape หน่วยเป็นจุด (อ่าน-อย่างเดียว) **float** |
| virtual **float** [get_Y](../ishape/get_y/)() | รับพิกัด y ของมุมซ้ายบนของ shape หน่วยเป็นจุด (อ่าน-อย่างเดียว) **float** |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | ส่งกลับตำแหน่งของ shape ใน z-order (Shapes[0] คือ shape ที่อยู่ด้านหลัง, Shapes[Shapes.Count - 1] คือ shape ที่อยู่ด้านหน้า) (อ่าน-อย่างเดียว) **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | ส่งกลับ shape placeholder พื้นฐาน (shape จากเลย์เอาต์หรือสไลด์แม่ที่ shape ปัจจุบันสืบทอด) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับออบเจ็กต์ |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | ส่งกลับสำเนา path ของรูปเรขาคณิตของ shape พิกัดอ้างอิงจากมุมซ้ายบนของ shape |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการแฮชออบเจ็กต์กำหนดเอง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | ส่งกลับ thumbnail ของ shape (ค่าเริ่มต้นใช้ประเภทขอบเขต thumbnail ของ shape [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/)) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | ส่งกลับ thumbnail ของ shape |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์ (อนาล็อกของเมธอด C# [System.Object.GetType()](../../system/object/gettype/)) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType (อนาล็อกของ operator C# 'is') |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง C# lock() เพื่อทำการล็อค เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการโคลนประเภทกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์และเริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก (ไม่ได้คัดลอกข้อมูลจริง เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับคลาสย่อย) |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย (ไม่ได้คัดลอกข้อมูลจริง เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับคลาสย่อย) |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำ specialize ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำ specialize ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่กำหนด |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | ระบุว่า shape นี้ไม่ใช่ placeholder |
| virtual void [Reroute](./reroute/)() | ปรับเส้นทาง connector ให้ใช้เส้นทางสั้นที่สุดระหว่าง shape ที่เชื่อมต่อ |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | ตั้งค่าข้อความอธิบายทางเลือกที่เชื่อมโยงกับ shape (เขียน [System::String](../../system/string/)) |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งค่าชื่อเรื่องของข้อความอธิบายทางเลือกที่เชื่อมโยงกับ shape (เขียน [System::String](../../system/string/)) |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | คุณสมบัติกำหนดว่า shape จะถูกแสดงผลในโหมดขาว-ดำอย่างไร (เขียน [Slides::BlackWhiteMode](../blackwhitemode/)) |
| virtual void [set_EndShapeConnectedTo](./set_endshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) | ตั้งค่า shape ที่เชื่อมต่อกับจุดสิ้นสุดของ connector (เขียน [IShape](../ishape/)) |
| virtual void [set_EndShapeConnectionSiteIndex](./set_endshapeconnectionsiteindex/)(**uint32_t**) | ตั้งค่าดัชนีของจุดเชื่อมต่อสำหรับ shape ปลาย (เขียน **uint32_t**) |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของเฟรม shape (เขียน [IShapeFrame](../ishapeframe/)) |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ตั้งค่าความสูงของ shape หน่วยเป็นจุด (เขียน **float**) |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | กำหนดว่ shape จะถูกซ่อนหรือไม่ (เขียน **bool**) |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่า hyperlink ที่กำหนดสำหรับการคลิกเมาส์ (เขียน [IHyperlink](../ihyperlink/)) |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่า hyperlink ที่กำหนดสำหรับการวางเมาส์ (เขียน [IHyperlink](../ihyperlink/)) |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ตั้งค่าออปชัน 'Mark as decorative' (อ่าน-เขียน **bool**) |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | ตั้งค่าชื่อของ shape (เขียน [System::String](../../system/string/)) |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของเฟรม shape ดิบ (เขียน [IShapeFrame](../ishapeframe/)) |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | ตั้งค่าจำนวนองศาที่ shape ถูกหมุนรอบแกน Z (ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา, ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา) (เขียน **float**) |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | ตั้งค่าประเภท preset ของเรขาคณิต (หมายเหตุ: การเปลี่ยนค่าจะทำให้ค่าการปรับทั้งหมดรีเซ็ตเป็นค่าเริ่มต้น) (เขียน [Slides::ShapeType](../shapetype/)) |
| virtual void [set_StartShapeConnectedTo](./set_startshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) | ตั้งค่า shape ที่เชื่อมต่อกับจุดเริ่มต้นของ connector (เขียน [IShape](../ishape/)) |
| virtual void [set_StartShapeConnectionSiteIndex](./set_startshapeconnectionsiteindex/)(**uint32_t**) | ตั้งค่าดัชนีของจุดเชื่อมต่อสำหรับ shape เริ่มต้น (เขียน **uint32_t**) |
| virtual void [set_Width](../ishape/set_width/)(**float**) | ตั้งค่าความกว้างของ shape หน่วยเป็นจุด (เขียน **float**) |
| virtual void [set_X](../ishape/set_x/)(**float**) | ตั้งค่าพิกัด x ของมุมซ้ายบนของ shape หน่วยเป็นจุด (เขียน **float**) |
| virtual void [set_Y](../ishape/set_y/)(**float**) | ตั้งค่าพิกัด y ของมุมซ้ายบนของ shape หน่วยเป็นจุด (เขียน **float**) |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | อัปเดตรูปเรขาคณิตของ shape จากอ็อบเจ็กต์ [IGeometryPath](../igeometrypath/) พิกัดต้องอิงจากมุมซ้ายบนของ shape เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/) |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | อัปเดตรูปเรขาคณิตของ shape จากอาร์เรย์ของ [IGeometryPath](../igeometrypath/) พิกัดต้องอิงจากมุมซ้ายบนของ shape เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า template argument ที่ n-th ให้เป็น weak pointer (แทน shared) เพื่อให้สามารถสลับเป็นโหมด weak ในคอนเทนเนอร์ |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงออบเจ็กต์กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตาม construct C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง C# lock() เพื่อปลดล็อค เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหา [Shape](../shape/) เป็นไฟล์ SVG |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหา [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์และคืนพื้นที่โครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IGeometryShape](../igeometryshape/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)