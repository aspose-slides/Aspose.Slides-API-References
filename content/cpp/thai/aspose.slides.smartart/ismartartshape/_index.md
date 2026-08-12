---
title: ISmartArtShape
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แสดงถึงรูปทรงภายในแผนภาพ SmartArt
type: docs
weight: 40
url: /th/aspose.slides.smartart/ismartartshape/
---
## ISmartArtShape คลาส


แสดงถึงรูปทรงภายใน [SmartArt](../smartart/) ไดอะแกรม

```cpp
class ISmartArtShape : public virtual Aspose::Slides::IGeometryShape
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่า placeholder properties ให้เป็นค่าที่ระบุ |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../../aspose.slides/ishapeelement/)\>\> [CreateShapeElements](../../aspose.slides/igeometryshape/createshapeelements/)() | สร้างและคืนค่า array ของ shape's elements |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่จำนวน NaN สองค่าได้รับการพิจารณาเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่จำนวน NaN สองค่าได้รับการพิจารณาเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../../aspose.slides/iadjustvalue/)\> [get_Adjustment](../../aspose.slides/igeometryshape/get_adjustment/)(**int32_t**) | คืนค่าการปรับของ shape ที่ตำแหน่งที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)\> [get_Adjustments](../../aspose.slides/igeometryshape/get_adjustments/)() | คืนค่าคอลเลกชันของค่าการปรับของ shape. อ่านอย่างเดียว [IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/) |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | คืนค่า alternative text ที่เชื่อมโยงกับ shape. อ่าน [System::String](../../system/string/) |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | คืนค่าชื่อเรื่องของ alternative text ที่เชื่อมโยงกับ shape. อ่าน [System::String](../../system/string/) |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | Property ระบุว่ารูปทรงจะเรนเดอร์อย่างไรในโหมดแสดงผลสีขาว-ดำ. อ่าน [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | คืนค่าจำนวน connection sites บน shape. อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | คืนค่าข้อมูล custom ของ shape. อ่านอย่างเดียว [ICustomData](../../aspose.slides/icustomdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | คืนค่าออบเจ็กต์ [EffectFormat](../../aspose.slides/effectformat/) ซึ่งบรรจุ pixel effects ที่ใช้กับ shape. อ่านอย่างเดียว [IEffectFormat](../../aspose.slides/ieffectformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | คืนค่าออบเจ็กต์ [FillFormat](../../aspose.slides/fillformat/) ซึ่งบรรจุ fill formatting properties สำหรับ shape. อ่านอย่างเดียว [IFillFormat](../../aspose.slides/ifillformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | คืนค่า property ของ shape frame. อ่าน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | รับความสูงของ shape วัดเป็นจุด. อ่าน **float** |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | กำหนดว่ารูปทรงถูกซ่อนไหม. อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | คืนค่า hyperlink ที่กำหนดสำหรับการคลิกเมาส์. อ่าน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | ตัวจัดการ Hyperlinks อ่านอย่างเดียว [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | คืนค่า hyperlink ที่กำหนดสำหรับการเมาน์เมาส์โอเวอร์. อ่าน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | กำหนดว่ารูปทรงถูกจัดกลุ่มไหม. อ่านอย่างเดียว **bool** |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | กำหนดว่ารูปทรงเป็น TextHolder ไหม. อ่านอย่างเดียว **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | คืนค่าออบเจ็กต์ [LineFormat](../../aspose.slides/lineformat/) ซึ่งบรรจุ line formatting properties สำหรับ shape. อ่านอย่างเดียว [ILineFormat](../../aspose.slides/ilineformat/) |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | คืนค่าชื่อของ shape. อ่าน [System::String](../../system/string/) |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | คืนค่า identifier ที่มีขอบเขตในสไลด์และคงที่ตลอดอายุของ shape เพื่อให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้อย่างเชื่อถือจากทุกตำแหน่งในเอกสาร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | คืนวัตถุ parent [GroupShape](../../aspose.slides/groupshape/) หาก shape ถูกจัดกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [IGroupShape](../../aspose.slides/igroupshape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | คืนค่า placeholder สำหรับ shape. อ่านอย่างเดียว [IPlaceholder](../../aspose.slides/iplaceholder/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | คืนค่า presentation. อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | คืนค่า property ของ raw shape frame. อ่าน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | คืนค่าจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | คืนค่า lock ของ shape. อ่านอย่างเดียว [IBaseShapeLock](../../aspose.slides/ibaseshapelock/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../../aspose.slides/ishapestyle/)\> [get_ShapeStyle](../../aspose.slides/igeometryshape/get_shapestyle/)() | คืนค่า object ของ style ของ shape. อ่านอย่างเดียว [IShapeStyle](../../aspose.slides/ishapestyle/) |
| virtual [Aspose::Slides::ShapeType](../../aspose.slides/shapetype/) [get_ShapeType](../../aspose.slides/igeometryshape/get_shapetype/)() | คืนค่า geometry preset type. หมายเหตุ: เมื่อค่าเปลี่ยนทั้งหมดของ adjustment values จะรีเซ็ตเป็นค่าเริ่มต้น. อ่าน [Slides::ShapeType](../../aspose.slides/shapetype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | คืนค่า base slide. อ่านอย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() | คืนข้อความของ shape [SmartArt](../smartart/). อ่านอย่างเดียว [ITextFrame](../../aspose.slides/itextframe/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | คืนค่าออบเจ็กต์ [ThreeDFormat](../../aspose.slides/threedformat/) ซึ่งบรรจุ line formatting properties สำหรับ shape. อ่านอย่างเดียว [IThreeDFormat](../../aspose.slides/ithreedformat/) |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | คืนค่า identifier ภายในที่มีขอบเขตใน presentation เพื่อใช้โดย add-in หรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม ดังนั้นไม่ควรถือเป็นคีย์ที่เป็นเอกลักษณ์ถาวร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/) |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | รับความกว้างของ shape วัดเป็นจุด. อ่าน **float** |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | รับค่า x-coordinate ของมุมซ้ายบนของ shape วัดเป็นจุด. อ่าน **float** |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | รับค่า y-coordinate ของมุมซ้ายบนของ shape วัดเป็นจุด. อ่าน **float** |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | คืนค่าตำแหน่งของ shape ใน z-order. Shapes[0] คืน shape ที่อยู่ด้านหลังของ z-order, และ Shapes[Shapes.Count - 1] คืน shape ที่อยู่ด้านหน้า. อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | คืน shape placeholder พื้นฐาน (shape จาก layout หรือ master slide ที่ shape ปัจจุบันสืบทอดมาจาก) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\> [GetGeometryPaths](../../aspose.slides/igeometryshape/getgeometrypaths/)() | คืนสำเนา path ของ geometry shape. พิกัดสัมพันธ์กับมุมซ้ายบนของ shape |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | แนวคิดคล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของออบเจ็กต์แบบกำหนดเอง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | คืน thumbnail ของ shape. ประเภท bounds ของ shape thumbnail [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) ถูกใช้เป็นค่าเริ่มต้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | คืน thumbnail ของ shape |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. แนวคิดคล้ายการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C# |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. แนวคิดคล้ายโอเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | แนวคิดคล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทแบบกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมายค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | ทำการอ้างอิงเปรียบเทียบอ็อบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของ string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำเฉพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของ strings |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่า shared reference count ตามค่าที่ระบุ |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | กำหนดว่า shape นี้ไม่ใช่ placeholder |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | ตั้งค่า alternative text ที่เชื่อมโยงกับ shape. เขียน [System::String](../../system/string/) |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งค่าชื่อเรื่องของ alternative text ที่เชื่อมโยงกับ shape. เขียน [System::String](../../system/string/) |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | Property ระบุว่ารูปทรงจะเรนเดอร์อย่างไรในโหมดแสดงผลสีขาว-ดำ. เขียน [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | ตั้งค่า property ของ shape frame. เขียน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | ตั้งค่าสูงของ shape วัดเป็นจุด. เขียน **float** |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | กำหนดว่ารูปทรงถูกซ่อนไหม. เขียน **bool** |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | ตั้งค่า hyperlink ที่กำหนดสำหรับการคลิกเมาส์. เขียน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | ตั้งค่า hyperlink ที่กำหนดสำหรับการเมาน์เมาส์โอเวอร์. เขียน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | ตั้งค่า 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | ตั้งค่าชื่อของ shape. เขียน [System::String](../../system/string/) |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | ตั้งค่า property ของ raw shape frame. เขียน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | ตั้งค่าจำนวนองศาที่ shape ที่ระบุถูกหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. เขียน **float** |
| virtual void [set_ShapeType](../../aspose.slides/igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../../aspose.slides/shapetype/)) | ตั้งค่า geometry preset type. หมายเหตุ: เมื่อค่าเปลี่ยนทั้งหมดของ adjustment values จะรีเซ็ตเป็นค่าเริ่มต้น. เขียน [Slides::ShapeType](../../aspose.slides/shapetype/) |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | ตั้งค่าความกว้างของ shape วัดเป็นจุด. เขียน **float** |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | ตั้งค่าค่า x-coordinate ของมุมซ้ายบนของ shape วัดเป็นจุด. เขียน **float** |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | ตั้งค่าค่า y-coordinate ของมุมซ้ายบนของ shape วัดเป็นจุด. เขียน **float** |
| virtual void [SetGeometryPath](../../aspose.slides/igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>) | ปรับ geometry ของ shape จากออบเจ็กต์ [IGeometryPath](../../aspose.slides/igeometrypath/). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../../aspose.slides/shapetype/)) เป็น [ShapeType::Custom](../../aspose.slides/shapetype/) |
| virtual void [SetGeometryPaths](../../aspose.slides/igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\>) | ปรับ geometry ของ shape จากอาร์เรย์ของ [IGeometryPath](../../aspose.slides/igeometrypath/). พิกัดต้องสัมพันธ์กับมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../../aspose.slides/shapetype/)) เป็น [ShapeType::Custom](../../aspose.slides/shapetype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า template argument ที่ n-th เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็น weak mode |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของ shared reference counter |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่า shared reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่า shared reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | แนวคิดคล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์แบบกำหนดเองเป็น string |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่า weak reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่า weak reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหา [Shape](../../aspose.slides/shape/) เป็นไฟล์ SVG |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหา [Shape](../../aspose.slides/shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยทุกโครงสร้างข้อมูลภายใน |
## ดูเพิ่มเติม

* คลาส [IGeometryShape](../../aspose.slides/igeometryshape/)
* เนมสเปซ [Aspose::Slides::SmartArt](../)
* ไลบรารี [Aspose.Slides](../../)