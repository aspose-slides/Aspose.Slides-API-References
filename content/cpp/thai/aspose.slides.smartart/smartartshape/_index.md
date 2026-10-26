---
title: SmartArtShape
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แทนรูปแบบ SmartArt shape
type: docs
weight: 105
url: /th/aspose.slides.smartart/smartartshape/
---
## SmartArtShape คลาส

แทนรูปแบบ [SmartArt](../smartart/) shape

```cpp
class SmartArtShape : public Aspose::Slides::GeometryShape,
                      public Aspose::Slides::SmartArt::ISmartArtShape
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณลักษณะของ placeholder ให้เป็นค่าที่ระบุ |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../../aspose.slides/ishapeelement/)\>\> [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements/)() override | สร้างและคืนค่าอาร์เรย์ขององค์ประกอบของ shape |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ถือว่า NaN สองค่ามีค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ถือว่า NaN สองค่ามีค่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../../aspose.slides/iadjustvalue/)\> [get_Adjustment](../../aspose.slides/geometryshape/get_adjustment/)(**int32_t**) override | คืนค่าการปรับของ shape ที่ตำแหน่งที่ระบุ |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)\> [get_Adjustments](../../aspose.slides/geometryshape/get_adjustments/)() override | คืนคอลเลกชันของค่าการปรับของ shape. อ่านอย่างเดียว [IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/). |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | คืนข้อความทางเลือกที่เชื่อมโยงกับ shape. อ่าน [System::String](../../system/string/). |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | คืนชื่อเรื่องของข้อความทางเลือกที่เชื่อมโยงกับ shape. อ่าน [System::String](../../system/string/). |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | คุณสมบัติระบุว่ารูปร่างจะถูกแสดงแบบสีขาว-ดำอย่างไร. อ่าน [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/). |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | คืนจำนวนจุดเชื่อมต่อบน shape. อ่านอย่างเดียว **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | คืนข้อมูลกำหนดเองของ shape. อ่านอย่างเดียว [ICustomData](../../aspose.slides/icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | คืนอ็อบเจ็กต์ [EffectFormat](../../aspose.slides/effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับ shape. หมายเหตุ: สามารถคืนค่า null สำหรับ shape ประเภทบางอย่างที่ไม่มีคุณสมบัติเอฟเฟกต์. อ่านอย่างเดียว [IEffectFormat](../../aspose.slides/ieffectformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | คืนอ็อบเจ็กต์ [FillFormat](../../aspose.slides/fillformat/) ที่มีคุณสมบัติการเติมสีสำหรับ shape. หมายเหตุ: สามารถคืนค่า null สำหรับ shape ประเภทบางอย่างที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว [IFillFormat](../../aspose.slides/ifillformat/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | คืนคุณสมบัติของเฟรม shape. อ่าน [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | รับความสูงของ shape หน่วยเป็น point. อ่าน **float**. |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | กำหนดว่า shape ถูกซ่อนไปหรือไม่. อ่าน **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | คืน hyperlink ที่กำหนดสำหรับการคลิกเมาส์. อ่าน [IHyperlink](../../aspose.slides/ihyperlink/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | คืนผู้จัดการ hyperlink. อ่านอย่างเดียว [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | คืน hyperlink ที่กำหนดสำหรับการวางเมาส์เหนือ. อ่าน [IHyperlink](../../aspose.slides/ihyperlink/). |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool**. |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | กำหนดว่า shape ถูกจัดกลุ่มหรือไม่. อ่านอย่างเดียว **bool**. |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | กำหนดว่า shape เป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | คืนอ็อบเจ็กต์ [LineFormat](../../aspose.slides/lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape. หมายเหตุ: สามารถคืนค่า null สำหรับ shape ประเภทบางอย่างที่ไม่มีคุณสมบัติการจัดรูปแบบเส้น. อ่านอย่างเดียว [ILineFormat](../../aspose.slides/ilineformat/). |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | คืนชื่อของ shape. ต้องไม่เป็น null. ใช้ค่าสตริงว่างหากต้องการ. อ่าน [System::String](../../system/string/). |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | คืนตัวระบุที่ไม่ซ้ำเฉพาะสไลด์ที่คงที่ตลอดอายุของ shape และช่วยให้ PowerPoint หรือโค้ด interop อ้างอิง shape ได้อย่างน่าเชื่อถือจากทุกส่วนของเอกสาร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | คืนอ็อบเจ็กต์พาเรนต์ [GroupShape](../../aspose.slides/groupshape/) หาก shape ถูกจัดกลุ่ม. มิฉะนั้นคืน null. อ่านอย่างเดียว [IGroupShape](../../aspose.slides/igroupshape/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | คืน placeholder สำหรับ shape. คืน null หาก shape ไม่มี placeholder. อ่านอย่างเดียว [IPlaceholder](../../aspose.slides/iplaceholder/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | คืนพาเรนต์พรีเซนเทชันของสไลด์. อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | คืนคุณสมบัติของเฟรม shape แบบดิบ. อ่าน [IShapeFrame](../../aspose.slides/ishapeframe/). |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | คืนจำนวนองศาที่ shape ระบุหมุนรอบแกน z. ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา. อ่าน **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | คืนการล็อกของ shape. อ่านอย่างเดียว [IBaseShapeLock](../../aspose.slides/ibaseshapelock/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../../aspose.slides/ishapestyle/)\> [get_ShapeStyle](../../aspose.slides/geometryshape/get_shapestyle/)() override | คืนอ็อบเจ็กต์สไตล์ของ shape. อ่านอย่างเดียว [IShapeStyle](../../aspose.slides/ishapestyle/). |
| [Aspose::Slides::ShapeType](../../aspose.slides/shapetype/) [get_ShapeType](./get_shapetype/)() override | คืนประเภท preset ของเรขาคณิต. หมายเหตุ: เมื่อค่าถูกเปลี่ยนค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น. อ่าน [Slides::ShapeType](../../aspose.slides/shapetype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | คืนสไลด์พาเรนต์ของ shape. อ่านอย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() override | คืนข้อความของ shape [SmartArt](../smartart/). อ่านอย่างเดียว [ITextFrame](../../aspose.slides/itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | คืนอ็อบเจ็กต์ [ThreeDFormat](../../aspose.slides/threedformat/) ที่มีคุณสมบัติเอฟเฟกต์ 3D สำหรับ shape. หมายเหตุ: สามารถคืนค่า null สำหรับ shape ประเภทบางอย่างที่ไม่มีคุณสมบัติ 3D. อ่านอย่างเดียว [IThreeDFormat](../../aspose.slides/ithreedformat/). |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | คืนตัวระบุภายในที่กำหนดขอบเขตระดับพรีเซนเทชันสำหรับใช้โดย add-in หรือโค้ดอื่น. เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, จึงไม่ควรถือว่าเป็นคีย์ที่ไม่ซ้ำแบบถาวร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/). |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | รับความกว้างของ shape หน่วยเป็น point. อ่าน **float**. |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | รับพิกัด X ของมุมซ้ายบนของ shape หน่วยเป็น point. อ่าน **float**. |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | รับพิกัด Y ของมุมซ้ายบนของ shape หน่วยเป็น point. อ่าน **float**. |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | คืนตำแหน่งของ shape ใน z-order. Shapes[0] คืน shape ที่อยู่ด้านหลังสุด, Shapes[Shapes.Count - 1] คืน shape ที่อยู่ด้านหน้าสุด. อ่านอย่างเดียว **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | คืน shape placeholder พื้นฐาน (shape จากเลเอาต์หรือสไลด์มาสเตอร์ที่ shape ปัจจุบันสืบทอดมาจาก) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\> [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths/)() override | คืนสำเนา path ของ shape เรขาคณิต. พิกัดอิงตามมุมซ้ายบนของ shape |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | แนวคิดคล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์กำหนดเองได้ |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | คืน thumbnail ของ shape. ชนิด bounds ของ thumbnail [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) ถูกใช้เป็นค่าเริ่มต้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | คืน thumbnail ของ shape |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. แนวคิดคล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | รับขอบเขตที่มองเห็นของ shape ที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. แนวคิดคล้ายออพเรเตอร์ C# 'is' |
| void [Lock](../../system/object/lock/)() | ทำตามคำสั่ง lock() ของ C# เพื่อล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | แนวคิดคล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทกำหนดเองได้ |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้คลาสย่อยคัดลอกได้ |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้คลาสย่อยคัดลอกได้ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี strings |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่า shared reference count ตามค่าที่ระบุ |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | กำหนดว่า shape นี้ไม่ใช่ placeholder |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | ตั้งข้อความทางเลือกที่เชื่อมโยงกับ shape. เขียน [System::String](../../system/string/) |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | ตั้งชื่อเรื่องของข้อความทางเลือกที่เชื่อมโยงกับ shape. เขียน [System::String](../../system/string/) |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | คุณสมบัติระบุว่ารูปร่างจะถูกแสดงแบบสีขาว-ดำอย่างไร. เขียน [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | ตั้งคุณสมบัติของเฟรม shape. เขียน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | ตั้งความสูงของ shape หน่วยเป็น point. เขียน **float** |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | กำหนดว่า shape ถูกซ่อนไปหรือไม่. เขียน **bool** |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | ตั้ง hyperlink ที่กำหนดสำหรับการคลิกเมาส์. เขียน [IHyperlink](../../aspose.slides/ihyperlink/) |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | ตั้ง hyperlink ที่กำหนดสำหรับการวางเมาส์เหนือ. เขียน [IHyperlink](../../aspose.slides/ihyperlink/) |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | ตั้งตัวเลือก 'Mark as decorative' เขียน/อ่าน **bool** |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | ตั้งชื่อของ shape. ต้องไม่เป็น null. ใช้ค่าสตริงว่างหากต้องการ. เขียน [System::String](../../system/string/) |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | ตั้งคุณสมบัติของเฟรม shape แบบดิบ. เขียน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | ตั้งจำนวนองศาที่ shape ระบุหมุนรอบแกน z. ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา. เขียน **float** |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../../aspose.slides/shapetype/)) override | ตั้งประเภท preset ของเรขาคณิต. หมายเหตุ: เมื่อค่าถูกเปลี่ยนค่าการปรับทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น. เขียน [Slides::ShapeType](../../aspose.slides/shapetype/) |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | ตั้งความกว้างของ shape หน่วยเป็น point. เขียน **float** |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | ตั้งพิกัด X ของมุมซ้ายบนของ shape หน่วยเป็น point. เขียน **float** |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | ตั้งพิกัด Y ของมุมซ้ายบนของ shape หน่วยเป็น point. เขียน **float** |
| void [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>) override | อัปเดตเรขาคณิตของ shape จากอ็อบเจ็กต์ [IGeometryPath](../../aspose.slides/igeometrypath/). พิกัดต้องอิงตามมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../../aspose.slides/shapetype/)) เป็น [ShapeType::Custom](../../aspose.slides/shapetype/) |
| void [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\>) override | อัปเดตเรขาคณิตของ shape จากอาร์เรย์ของ [IGeometryPath](../../aspose.slides/igeometrypath/). พิกัดต้องอิงตามมุมซ้ายบนของ shape. เปลี่ยนประเภทของ shape ([ShapeType](../../aspose.slides/shapetype/)) เป็น [ShapeType::Custom](../../aspose.slides/shapetype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงแบบ shared |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่า shared reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่า shared reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | แนวคิดคล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้แปลงอ็อบเจ็กต์กำหนดเองเป็น string ได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำตามโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่า weak reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่า weak reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหา [Shape](../../aspose.slides/shape/) เป็นไฟล์ SVG |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | บันทึกเนื้อหา [Shape](../../aspose.slides/shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ลบโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [GeometryShape](../../aspose.slides/geometryshape/)
* คลาส [ISmartArtShape](../ismartartshape/)
* เนมสเปซ [Aspose::Slides::SmartArt](../)
* ไลบรารี [Aspose.Slides](../../)