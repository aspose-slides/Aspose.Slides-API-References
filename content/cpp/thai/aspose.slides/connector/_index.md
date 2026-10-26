---
title: Connector
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงถึงตัวเชื่อมต่อ.
type: docs
weight: 482
url: /th/aspose.slides/connector/
---
## คลาส Connector

แสดงถึงตัวเชื่อมต่อ.

```cpp
class Connector : public Aspose::Slides::GeometryShape,
                  public Aspose::Slides::IConnector
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder เป็นค่าเฉพาะที่ระบุ. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | สร้างและคืนค่าอาร์เรย์ขององค์ประกอบของ shape. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์แบบอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขจุดลอยตามสไตล์ C# ซึ่งสองค่า NaN จะถือว่าสเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขจุดลอยตามสไตล์ C# ซึ่งสองค่า NaN จะถือว่าสเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | คืนค่าการปรับของ shape ที่ตำแหน่งที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | คืนคอลเลกชันของค่าการปรับของ shape. อ่านอย่างเดียว [IAdjustValueCollection](../iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | คืนข้อความสำรองที่เชื่อมโยงกับ shape. อ่าน [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | คืนหัวข้อของข้อความสำรองที่เชื่อมโยงกับ shape. อ่าน [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | คุณสมบัติกำหนดว่ารูปร่างจะเรนเดอร์ในโหมดแสดงผลสีขาว-ดำอย่างไร. อ่าน [Slides::BlackWhiteMode](../blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | คืนจำนวนจุดเชื่อมต่อบน shape. อ่านอย่างเดียว **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IConnectorLock](../iconnectorlock/)\> [get_ConnectorLock](./get_connectorlock/)() override | คืนล็อกของ connector. อ่านอย่างเดียว [IConnectorLock](../iconnectorlock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | คืนข้อมูลแบบกำหนดของ shape. อ่านอย่างเดียว [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | คืนอ็อบเจ็กต์ [EffectFormat](../effectformat/) ที่มีเอฟเฟ็กต์พิกเซลที่ใช้กับ shape. หมายเหตุ: อาจคืนค่า null สำหรับประเภท shape บางอย่างที่ไม่มีคุณสมบัติเอฟเฟ็กต์. อ่านอย่างเดียว [IEffectFormat](../ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_EndShapeConnectedTo](./get_endshapeconnectedto/)() override | คืน shape ที่เชื่อมต่อปลายของ connector. อ่าน [IShape](../ishape/). |
| **uint32_t** [get_EndShapeConnectionSiteIndex](./get_endshapeconnectionsiteindex/)() override | คืนดัชนีของจุดเชื่อมต่อสำหรับ shape ปลาย. อ่าน **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | คืนอ็อบเจ็กต์ [FillFormat](../fillformat/) ที่มีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับ shape. หมายเหตุ: อาจคืนค่า null สำหรับ shape บางประเภทที่ไม่มีคุณสมบัติการเติม. อ่านอย่างเดียว [IFillFormat](../ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | คืนคุณสมบัติของเฟรม shape. อ่าน [IShapeFrame](../ishapeframe/). |
| **float** [get_Height](../shape/get_height/)() override | รับความสูงของ shape หน่วยเป็นจุด. อ่าน **float**. |
| **bool** [get_Hidden](../shape/get_hidden/)() override | ตรวจสอบว่า shape ถูกซ่อนไว้หรือไม่. อ่าน **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | คืนไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน [IHyperlink](../ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | คืนผู้จัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | คืนไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ. อ่าน [IHyperlink](../ihyperlink/). |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | รับตัวเลือก 'Mark as decorative' แบบอ่าน/เขียน **bool**. |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | ตรวจสอบว่า shape อยู่ในกลุ่มหรือไม่. อ่านอย่างเดียว **bool**. |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | ตรวจสอบว่า shape เป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | คืนอ็อบเจ็กต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape. หมายเหตุ: อาจคืนค่า null สำหรับ shape บางประเภทที่ไม่มีคุณสมบัติเส้น. อ่านอย่างเดียว [ILineFormat](../ilineformat/). |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | คืนชื่อของ shape. ต้องไม่เป็น null. หากจำเป็นให้ใช้ค่าว่าง. อ่าน [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | คืนหมายเลขประจำตัวที่ไม่ซ้ำกันระดับสไลด์ที่คงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้อย่างน่าเชื่อถือจากที่ใดก็ได้ในเอกสาร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_UniqueId](../shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | คืนอ็อบเจ็กต์ [GroupShape](../groupshape/) พ่อแม่หาก shape อยู่ในกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [IGroupShape](../igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | คืน placeholder ของ shape. คืนค่า null หาก shape ไม่มี placeholder. อ่านอย่างเดียว [IPlaceholder](../iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | คืนการนำเสนอแม่ของสไลด์. อ่านอย่างเดียว [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | คืนคุณสมบัติของเฟรม shape ดิบ. อ่าน [IShapeFrame](../ishapeframe/). |
| **float** [get_Rotation](../shape/get_rotation/)() override | คืนจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบแกน z. ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา. อ่าน **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | คืนล็อกของ shape. อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | คืนอ็อบเจ็กต์สไตล์ของ shape. อ่านอย่างเดียว [IShapeStyle](../ishapestyle/). |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override | คืนประเภท [AutoShape](../autoshape/). อ่าน [Slides::ShapeType](../shapetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | คืนสไลด์แม่ของ shape. อ่านอย่างเดียว [IBaseSlide](../ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_StartShapeConnectedTo](./get_startshapeconnectedto/)() override | คืน shape ที่เชื่อมต่อจุดเริ่มต้นของ connector. อ่าน [IShape](../ishape/). |
| **uint32_t** [get_StartShapeConnectionSiteIndex](./get_startshapeconnectionsiteindex/)() override | คืนดัชนีของจุดเชื่อมต่อสำหรับ shape เริ่มต้น. อ่าน **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | คืนอ็อบเจ็กต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติ 3D ของ shape. หมายเหตุ: อาจคืนค่า null สำหรับ shape บางประเภทที่ไม่มีคุณสมบัติ 3D. อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/). |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | คืนตัวระบุภายในระดับการนำเสนอที่มุ่งใช้โดย add-in หรือโค้ดอื่น ๆ. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม, จึงไม่ควรใช้เป็นคีย์ที่คงที่. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/). |
| **float** [get_Width](../shape/get_width/)() override | รับความกว้างของ shape หน่วยเป็นจุด. อ่าน **float**. |
| **float** [get_X](../shape/get_x/)() override | รับค่าพิกัด x ของมุมซ้ายบนของ shape หน่วยเป็นจุด. อ่าน **float**. |
| **float** [get_Y](../shape/get_y/)() override | รับค่าพิกัด y ของมุมซ้ายบนของ shape หน่วยเป็นจุด. อ่าน **float**. |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | คืนตำแหน่งของ shape ในลำดับ z. Shapes[0] คืน shape ที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืน shape ที่อยู่ด้านหน้า. อ่านอย่างเดียว **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | คืน shape placeholder พื้นฐาน (shape จากเลย์เอาต์และ/หรือสไลด์แม่ที่ shape ปัจจุบันสืบทอดจาก). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | คืนสำเนาเส้นทางของรูปทรงเรขาคณิต. พิกัดสัมพันธ์กับมุมซ้ายบนของ shape. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์แบบกำหนดเองได้. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | คืนรูปย่อของ shape. ชนิดขอบเขตรูปย่อ [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ใช้เป็นค่าเริ่มต้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | คืนรูปย่อของ shape. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | รับขอบเขตภาพของ shape ที่คำนวณจากเนื้อหาที่แสดงผล. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และอนุญาตให้สร้างสำเนาในคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และอนุญาตให้สร้างสำเนาในคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | กำหนดว่า shape นี้ไม่ใช่ placeholder. |
| void [Reroute](./reroute/)() override | เปลี่ยนเส้นทางของ connector เพื่อให้ใช้เส้นทางที่สั้นที่สุดระหว่าง shape ที่เชื่อมต่อ. |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | ตั้งค่าข้อความสำรองที่เชื่อมโยงกับ shape. เขียน [System::String](../../system/string/). |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | ตั้งค่าหัวข้อของข้อความสำรองที่เชื่อมโยงกับ shape. เขียน [System::String](../../system/string/). |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | คุณสมบัติกำหนดว่ารูปร่างจะเรนเดอร์ในโหมดสีขาว-ดำอย่างไร. เขียน [Slides::BlackWhiteMode](../blackwhitemode/). |
| void [set_EndShapeConnectedTo](./set_endshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | ตั้งค่า shape ที่เชื่อมต่อปลายของ connector. เขียน [IShape](../ishape/). |
| void [set_EndShapeConnectionSiteIndex](./set_endshapeconnectionsiteindex/)(**uint32_t**) override | ตั้งค่าดัชนีของจุดเชื่อมต่อสำหรับ shape ปลาย. เขียน **uint32_t**. |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของเฟรม shape. เขียน [IShapeFrame](../ishapeframe/). |
| void [set_Height](../shape/set_height/)(**float**) override | ตั้งค่าความสูงของ shape หน่วยเป็นจุด. เขียน **float**. |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | กำหนดว่า shape จะซ่อนหรือไม่. เขียน **bool**. |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. เขียน [IHyperlink](../ihyperlink/). |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ. เขียน [IHyperlink](../ihyperlink/). |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | ตั้งค่าตัวเลือก 'Mark as decorative' แบบอ่าน/เขียน **bool**. |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | ตั้งค่า 이름ของ shape. ต้องไม่เป็น null. หากจำเป็นให้ใช้ค่าว่าง. เขียน [System::String](../../system/string/). |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของเฟรม shape ดิบ. เขียน [IShapeFrame](../ishapeframe/). |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | ตั้งค่าจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบแกน z. ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา. เขียน **float**. |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override | ตั้งค่าประเภท [AutoShape](../autoshape/). เขียน [Slides::ShapeType](../shapetype/). |
| void [set_StartShapeConnectedTo](./set_startshapeconnectedto/)([System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\>) override | ตั้งค่า shape ที่เชื่อมต่อจุดเริ่มต้นของ connector. เขียน [IShape](../ishape/). |
| void [set_StartShapeConnectionSiteIndex](./set_startshapeconnectionsiteindex/)(**uint32_t**) override | ตั้งค่าดัชนีของจุดเชื่อมต่อสำหรับ shape เริ่มต้น. เขียน **uint32_t**. |
| void [set_Width](../shape/set_width/)(**float**) override | ตั้งค่าความกว้างของ shape หน่วยเป็นจุด. เขียน **float**. |
| void [set_X](../shape/set_x/)(**float**) override | ตั้งค่าพิกัด x ของมุมซ้ายบนของ shape หน่วยเป็นจุด. เขียน **float**. |
| void [set_Y](../shape/set_y/)(**float**) override | ตั้งค่าพิกัด y ของมุมซ้ายบนของ shape หน่วยเป็นจุด. เขียน **float**. |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | อัปเดตรูป هندسية shape จากอ็อบเจ็กต์ [IGeometryPath](../igeometrypath/). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/). |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | อัปเดตรูป هندسية shape จากอาเรย์ของ [IGeometryPath](../igeometrypath/). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่คล้าย typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG. |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [GeometryShape](../geometryshape/)
* คลาส [IConnector](../iconnector/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)