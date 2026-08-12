---
title: GeometryShape
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นคลาสแม่สำหรับรูปทรงเรขาคณิตทั้งหมด.
type: docs
weight: 1080
url: /th/aspose.slides/geometryshape/
---
## GeometryShape คลาส

Represents the parent class for all geometric shapes.

```cpp
class GeometryShape : public Aspose::Slides::Shape,
                      public virtual Aspose::Slides::IGeometryShape
```

## เมธอด

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](./createshapeelements/)() override | สร้างและส่งกลับอาเรย์ขององค์ประกอบของ shape |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงแบบสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าแบบสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C#-style ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C#-style ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้ภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](./get_adjustment/)(**int32_t**) override | ส่งคืนค่าการปรับของ shape ที่ตำแหน่งดัชนีที่ระบุ |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](./get_adjustments/)() override | ส่งคืนคอลเลกชันของค่าการปรับของ shape อ่านอย่างเดียว [IAdjustValueCollection](../iadjustvaluecollection/) |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | ส่งคืนข้อความแทนที่เชื่อมโยงกับ shape อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | ส่งคืนหัวข้อของข้อความแทนที่เชื่อมโยงกับ shape อ่าน [System::String](../../system/string/) |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | คุณสมบัติกำหนดว่า shape จะเรนเดอร์ในโหมดแสดงผลสีขาวดำอย่างไร อ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | ส่งคืนจำนวนตำแหน่งการเชื่อมต่อบน shape อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | ส่งคืนข้อมูลกำหนดเองของ shape อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | ส่งคืนอ็อบเจ็กต์ [EffectFormat](../effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape หมายเหตุ: อาจส่งคืน null สำหรับ shape บางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์ อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | ส่งคืนอ็อบเจ็กต์ [FillFormat](../fillformat/) ที่มีคุณสมบัติดีไซน์การเติมสีสำหรับ shape หมายเหตุ: อาจส่งคืน null สำหรับ shape บางประเภทที่ไม่มีคุณสมบัติการเติมสี อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | ส่งคืนคุณสมบัติของกรอบ shape อ่าน [IShapeFrame](../ishapeframe/) |
| **float** [get_Height](../shape/get_height/)() override | รับความสูงของ shape ที่วัดเป็นจุด อ่าน **float** |
| **bool** [get_Hidden](../shape/get_hidden/)() override | กำหนดว่า shape ถูกซ่อนหรือไม่ อ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | ส่งคืน hyperlink ที่กำหนดสำหรับคลิกเมาส์ อ่าน [IHyperlink](../ihyperlink/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | ส่งคืนผู้จัดการ hyperlink อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | ส่งคืน hyperlink ที่กำหนดสำหรับเมาส์วางเหนือ อ่าน [IHyperlink](../ihyperlink/) |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่ อ่านอย่างเดียว **bool** |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | ส่งคืนอ็อบเจ็กต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติการฟอร์แมตเส้นสำหรับ shape หมายเหตุ: อาจส่งคืน null สำหรับ shape บางประเภทที่ไม่มีคุณสมบัติเส้น อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | ส่งคืนชื่อของ shape ต้องไม่เป็น null ใช้ค่าสตริงว่างหากจำเป็น อ่าน [System::String](../../system/string/) |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | ส่งคืนตัวระบุที่ไม่ซ้ำกันเชิงสไลด์ที่คงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape อย่างมั่นใจจากที่ใดก็ได้ในเอกสาร อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_UniqueId](../shape/get_uniqueid/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | ส่งคืนอ็อบเจ็กต์ [GroupShape](../groupshape/) พาเรนท์ หาก shape ถูกจัดกลุ่ม ไม่เช่นนั้นส่งคืน null อ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | ส่งคืน placeholder ของ shape ส่งคืน null หาก shape ไม่มี placeholder อ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | ส่งคืนพาเรนท์ presentation ของสไลด์ อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | ส่งคืนคุณสมบัติของกรอบ shape ดิบ อ่าน [IShapeFrame](../ishapeframe/) |
| **float** [get_Rotation](../shape/get_rotation/)() override | ส่งคืนจำนวนองศาที่ shape ที่ระบุหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา อ่าน **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | ส่งคืนการล็อกของ shape อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](./get_shapestyle/)() override | ส่งคืนอ็อบเจ็กต์สไตล์ของ shape อ่านอย่างเดียว [IShapeStyle](../ishapestyle/) |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() override | ส่งคืนประเภท geometry preset หมายเหตุ: เมื่อค่าเปลี่ยนแปลงค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าดีฟอลต์ อ่าน [Slides::ShapeType](../shapetype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | ส่งคืนสไลด์พาเรนท์ของ shape อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | ส่งคืนอ็อบเจ็กต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติเพิ่มเติม 3D สำหรับ shape หมายเหตุ: อาจส่งคืน null สำหรับ shape บางประเภทที่ไม่มีคุณสมบัติ 3D อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | ส่งคืนตัวระบุที่ใช้ภายในเชิง presentation ซึ่งออกแบบให้ใช้โดย add-in หรือโค้ดอื่น เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม จึงไม่ควรถือเป็นคีย์ที่ไม่ซ้ำกันถาวร อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/) |
| **float** [get_Width](../shape/get_width/)() override | รับความกว้างของ shape ที่วัดเป็นจุด อ่าน **float** |
| **float** [get_X](../shape/get_x/)() override | รับพิกัด x ของมุมซ้ายบนของ shape ที่วัดเป็นจุด อ่าน **float** |
| **float** [get_Y](../shape/get_y/)() override | รับพิกัด y ของมุมซ้ายบนของ shape ที่วัดเป็นจุด อ่าน **float** |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | ส่งคืนตำแหน่งของ shape ในลำดับ z Shapes[0] ส่งคืน shape ที่อยู่ด้านหลังของลำดับ z และ Shapes[Shapes.Count - 1] ส่งคืน shape ที่อยู่ด้านหน้า ของลำดับ z อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | ส่งคืน placeholder shape พื้นฐาน (shape จากเลเอาต์และ/หรือสไลด์มาสเตอร์ที่ shape ปัจจุบันสืบทอดมา) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](./getgeometrypaths/)() override | ส่งคืนสำเนาของเส้นทางของ geometry shape พิกัดอ้างอิงจากมุมซ้ายบนของ shape |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกจากเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์กำหนดเองได้ |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | ส่งคืนรูปย่อของ shape [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ชนิดขอบเขตรูปย่อของ shape ถูกใช้เป็นค่าเริ่มต้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | ส่งคืนรูปย่อของ shape |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นอนาล็อกจากการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | รับขอบเขตภาพของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่ targetType อธิบาย เป็นอนาล็อกจากโอเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกจากเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทกำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | กำหนดว่า shape นี้ไม่ใช่ placeholder |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | ตั้งค่าข้อความแทนที่เชื่อมโยงกับ shape เขียน [System::String](../../system/string/) |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | ตั้งค่าหัวข้อของข้อความแทนที่เชื่อมโยงกับ shape เขียน [System::String](../../system/string/) |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | คุณสมบัติกำหนดว่า shape จะเรนเดอร์ในโหมดแสดงผลสีขาวดำอย่างไร เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของกรอบ shape เขียน [IShapeFrame](../ishapeframe/) |
| void [set_Height](../shape/set_height/)(**float**) override | ตั้งค่าความสูงของ shape ที่วัดเป็นจุด เขียน **float** |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | กำหนดว่า shape ถูกซ่อนหรือไม่ เขียน **bool** |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่า hyperlink ที่กำหนดสำหรับคลิกเมาส์ เขียน [IHyperlink](../ihyperlink/) |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่า hyperlink ที่กำหนดสำหรับเมาส์วางเหนือ เขียน [IHyperlink](../ihyperlink/) |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | ตั้งค่าชื่อของ shape ต้องไม่เป็น null ใช้ค่าสตริงว่างหากจำเป็น เขียน [System::String](../../system/string/) |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของกรอบ shape ดิบ เขียน [IShapeFrame](../ishapeframe/) |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | ตั้งค่าจำนวนองศาที่ shape ที่ระบุหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา เขียน **float** |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override | ตั้งค่าประเภท geometry preset หมายเหตุ: เมื่อค่าเปลี่ยนแปลงค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าดีฟอลต์ เขียน [Slides::ShapeType](../shapetype/) |
| void [set_Width](../shape/set_width/)(**float**) override | ตั้งค่าความกว้างของ shape ที่วัดเป็นจุด เขียน **float** |
| void [set_X](../shape/set_x/)(**float**) override | ตั้งค่าพิกัด x ของมุมซ้ายบนของ shape ที่วัดเป็นจุด เขียน **float** |
| void [set_Y](../shape/set_y/)(**float**) override | ตั้งค่าพิกัด y ของมุมซ้ายบนของ shape ที่วัดเป็นจุด เขียน **float** |
| void [SetGeometryPath](./setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | อัปเดตเรขาคณิตของ shape จากอ็อบเจ็กต์ [IGeometryPath](../igeometrypath/) พิกัดต้องอ้างอิงจากมุมซ้ายบนของ shape เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/) |
| void [SetGeometryPaths](./setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | อัปเดตเรขาคณิตของ shape จากอาเรย์ของ [IGeometryPath](../igeometrypath/) พิกัดต้องอ้างอิงจากมุมซ้ายบนของ shape เปลี่ยนประเภทของ shape ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared) อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งค่าตัวนับอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกจากเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิง weak ควรไม่เรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิง weak ควรไม่เรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Shape](../shape/)
* คลาส [IGeometryShape](../igeometryshape/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)