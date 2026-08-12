---
title: SmartArt
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนของไดอะแกรม SmartArt
type: docs
weight: 66
url: /th/aspose.slides.smartart/smartart/
---
## คลาส SmartArt


แทนไดอะแกรม [SmartArt](./)

```cpp
class SmartArt : public Aspose::Slides::GraphicalObject,
                 public Aspose::Slides::SmartArt::ISmartArt
```

## เมธอด

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ NaN ทั้งสองถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ NaN ทั้งสองถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_AllNodes](./get_allnodes/)() override | คืนค่าคอลเลกชันของโหนดทั้งหมดในอ็อบเจ็กต์ [SmartArt](./). อ่านอย่างเดียว [ISmartArtNodeCollection](../ismartartnodecollection/) |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | คืนค่าข้อความทางเลือกที่เชื่อมโยงกับรูปทรง. อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | คืนค่าชื่อเรื่องของข้อความทางเลือกที่เชื่อมโยงกับรูปทรง. อ่าน [System::String](../../system/string/) |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | คุณสมบัติระบุว่ารูปทรงจะเรนเดอร์ในโหมดแสดงผลสีขาว-ดำอย่างไร.. อ่าน [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) |
| [SmartArtColorType](../smartartcolortype/) [get_ColorStyle](./get_colorstyle/)() override | คืนค่าลักษณะสีของอ็อบเจ็กต์ [SmartArt](./). อ่าน [SmartArtColorType](../smartartcolortype/) |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | คืนค่าจำนวนจุดเชื่อมต่อบนรูปทรง. อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | คืนค่าข้อมูลกำหนดเองของรูปทรง. อ่านอย่างเดียว [ICustomData](../../aspose.slides/icustomdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | คืนค่าอ็อบเจ็กต์ [EffectFormat](../../aspose.slides/effectformat/) ที่มีเอฟเฟ็กต์พิกเซลที่ใช้กับรูปทรง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติของเอฟเฟ็กต์. อ่านอย่างเดียว [IEffectFormat](../../aspose.slides/ieffectformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | คืนค่าอ็อบเจ็กต์ [FillFormat](../../aspose.slides/fillformat/) ที่มีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับรูปทรง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติมสี. อ่านอย่างเดียว [IFillFormat](../../aspose.slides/ifillformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | คืนค่าคุณสมบัติของกรอบรูปทรง. อ่าน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | คืนค่าการล็อคของรูปทรง. อ่านอย่างเดียว [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/) |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | รับความสูงของรูปทรงเป็นหน่วยจุด. อ่าน **float** |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | กำหนดว่ารูปทรงถูกซ่อนหรือไม่. อ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | คืนค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน [IHyperlink](../../aspose.slides/ihyperlink/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | คืนค่าตัวจัดการลิงก์ไฮเปอร์. อ่านอย่างเดียว [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | คืนค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการวางเมาส์. อ่าน [IHyperlink](../../aspose.slides/ihyperlink/) |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | กำหนดว่ารูปทรงเป็นกลุ่มหรือไม่. อ่านอย่างเดียว **bool** |
| **bool** [get_IsReversed](./get_isreversed/)() override | คืนค่าหรือกำหนดสถานะของไดอะแกรม [SmartArt](./) เกี่ยวกับ (จากซ้ายไปขวา) LTR หรือ (จากขวาไปซ้าย) RTL หากไดอะแกรมรองรับการกลับด้าน. อ่าน **bool** |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่. อ่านอย่างเดียว **bool** |
| [SmartArtLayoutType](../smartartlayouttype/) [get_Layout](./get_layout/)() override | คืนค่าเลย์เอาต์ของอ็อบเจ็กต์ [SmartArt](./). อ่าน [SmartArtLayoutType](../smartartlayouttype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | คืนค่าอ็อบเจ็กต์ [LineFormat](../../aspose.slides/lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติของเส้น. อ่านอย่างเดียว [ILineFormat](../../aspose.slides/ilineformat/) |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | คืนชื่อของรูปทรง. ต้องไม่เป็นค่า null. ใช้ค่าว่างหากจำเป็น. อ่าน [System::String](../../system/string/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_Node](./get_node/)(**int32_t**) override | คืนค่าโหนดจากคอลเลกชันของโหนดรากในอ็อบเจ็กต์ [SmartArt](./) ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_NodeFromAll](./get_nodefromall/)(**int32_t**) override | คืนค่าโหนดจากคอลเลกชันของโหนดทั้งหมดในอ็อบเจ็กต์ [SmartArt](./) ที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_Nodes](./get_nodes/)() override | คืนค่าคอลเลกชันของโหนดรากในอ็อบเจ็กต์ [SmartArt](./). อ่านอย่างเดียว [ISmartArtNodeCollection](../ismartartnodecollection/) |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | คืนค่าตัวระบุที่ไม่ซ้ำกันระดับสไลด์ซึ่งคงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงได้อย่างน่าเชื่อถือจากทุกส่วนของเอกสาร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | คืนค่าอ็อบเจ็กต์พาเรนต์ [GroupShape](../../aspose.slides/groupshape/) หากรูปทรงเป็นกลุ่ม. มิฉะนั้นจะคืนค่า null. อ่านอย่างเดียว [IGroupShape](../../aspose.slides/igroupshape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | คืนค่า placeholder ของรูปทรง. คืนค่า null หากรูปทรงไม่มี placeholder. อ่านอย่างเดียว [IPlaceholder](../../aspose.slides/iplaceholder/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | คืนค่าการนำเสนอพาเรนต์ของสไลด์. อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/) |
| [SmartArtQuickStyleType](../smartartquickstyletype/) [get_QuickStyle](./get_quickstyle/)() override | คืนค่าสตีลด่วนของอ็อบเจ็กต์ [SmartArt](./). อ่าน [SmartArtQuickStyleType](../smartartquickstyletype/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | คืนค่าคุณสมบัติเฟรมดิบของรูปทรง. อ่าน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | คืนค่าจำนวนองศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z. ค่าบวกบ่งบอกการหมุนตามเข็มนาฬิกา; ค่าลบบ่งบอกการหมุนทวนเข็มนาฬิกา. อ่าน **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | คืนค่าการล็อคของรูปทรง. อ่านอย่างเดียว [IBaseShapeLock](../../aspose.slides/ibaseshapelock/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | คืนค่าซไลด์พาเรนต์ของรูปทรง. อ่านอย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | คืนค่าอ็อบเจ็กต์ [ThreeDFormat](../../aspose.slides/threedformat/) ที่มีคุณสมบัติเอฟเฟ็กต์ 3 มิติสำหรับรูปทรง. หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ. อ่านอย่างเดียว [IThreeDFormat](../../aspose.slides/ithreedformat/) |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | คืนค่าตัวระบุภายในระดับการนำเสนอซึ่งตั้งใจใช้โดยแอดอินหรือโค้ดอื่น. เนื่องจากค่านี้สามารถกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรมได้ ดังนั้นจึงไม่ควรถือว่าเป็นคีย์ที่ไม่ซ้ำกันถาวร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/) |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | รับความกว้างของรูปทรงเป็นหน่วยจุด. อ่าน **float** |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | รับพิกัด x ของมุมซ้ายบนของรูปทรงเป็นหน่วยจุด. อ่าน **float** |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | รับพิกัด y ของมุมซ้ายบนของรูปทรงเป็นหน่วยจุด. อ่าน **float** |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | คืนตำแหน่งของรูปทรงในลำดับ z. Shapes[0] คืนรูปทรงที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปทรงที่อยู่ด้านหน้าของลำดับ z. อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | คืนรูปทรง placeholder พื้นฐาน (รูปทรงจากเลเอาต์และ/หรือสไลด์มาสเตอร์ที่รูปทรงปัจจุบันสืบทอดมาจาก) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อะแนล็กของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์กำหนดเอง |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | คืนภาพย่อของรูปทรง. [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) ชนิดขอบเขตภาพย่อของรูปทรงใช้เป็นค่าเริ่มต้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | คืนภาพย่อของรูปทรง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. อะแนล็กของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่ targetType ระบุหรือไม่. อะแนล็กของตัวดำเนินการ C# 'is' |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อะแนล็กของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมโดยค่าที่ระบุ |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | ตั้งค่าข้อความทางเลือกที่เชื่อมโยงกับรูปทรง. เขียน [System::String](../../system/string/) |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | ตั้งค่าชื่อเรื่องของข้อความทางเลือกที่เชื่อมโยงกับรูปทรง. เขียน [System::String](../../system/string/) |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | คุณสมบัติระบุว่ารูปทรงจะเรนเดอร์ในโหมดแสดงผลสีขาว-ดำอย่างไร.. เขียน [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) |
| void [set_ColorStyle](./set_colorstyle/)([SmartArtColorType](../smartartcolortype/)) override | ตั้งค่าลักษณะสีของอ็อบเจ็กต์ [SmartArt](./). เขียน [SmartArtColorType](../smartartcolortype/) |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของเฟรมรูปทรง. เขียน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | ตั้งค่าความสูงของรูปทรงเป็นหน่วยจุด. เขียน **float** |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | ตั้งค่าการซ่อนของรูปทรง. เขียน **bool** |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | ตั้งค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการคลิกเมาส์. เขียน [IHyperlink](../../aspose.slides/ihyperlink/) |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | ตั้งค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการวางเมาส์. เขียน [IHyperlink](../../aspose.slides/ihyperlink/) |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| void [set_IsReversed](./set_isreversed/)(**bool**) override | คืนค่าหรือกำหนดสถานะของไดอะแกรม [SmartArt](./) เกี่ยวกับ (จากซ้ายไปขวา) LTR หรือ (จากขวาไปซ้าย) RTL หากไดอะแกรมรองรับการกลับด้าน. เขียน **bool** |
| void [set_Layout](./set_layout/)([SmartArtLayoutType](../smartartlayouttype/)) override | ตั้งค่าเลย์เอาต์ของอ็อบเจ็กต์ [SmartArt](./). เขียน [SmartArtLayoutType](../smartartlayouttype/) |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | ตั้งชื่อของรูปทรง. ต้องไม่เป็น null. ใช้ค่าว่างหากจำเป็น. เขียน [System::String](../../system/string/) |
| void [set_QuickStyle](./set_quickstyle/)([SmartArtQuickStyleType](../smartartquickstyletype/)) override | ตั้งค่าสตีลด่วนของอ็อบเจ็กต์ [SmartArt](./). เขียน [SmartArtQuickStyleType](../smartartquickstyletype/) |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของเฟรมรูปทรงดิบ. เขียน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | ตั้งค่าจำนวนองศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z. ค่าบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา. เขียน **float** |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | ตั้งค่าความกว้างของรูปทรงเป็นหน่วยจุด. เขียน **float** |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | ตั้งค่าพิกัด x ของมุมซ้ายบนของรูปทรงเป็นหน่วยจุด. เขียน **float** |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | ตั้งค่าพิกัด y ของมุมซ้ายบนของรูปทรงเป็นหน่วยจุด. เขียน **float** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม. ควรไม่เรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่า. ควรไม่เรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อะแนล็กของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ควรไม่เรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ควรไม่เรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหาของ [Shape](../../aspose.slides/shape/) เป็นไฟล์ SVG |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | บันทึกเนื้อหาของ [Shape](../../aspose.slides/shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [GraphicalObject](../../aspose.slides/graphicalobject/)
* คลาส [ISmartArt](../ismartart/)
* เนมสเปซ [Aspose::Slides::SmartArt](../)
* ไลบรารี [Aspose.Slides](../../)