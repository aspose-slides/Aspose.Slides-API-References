---
title: Shape
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: แสดงถึงรูปทรงบนสไลด์หนึ่ง.
type: docs
weight: 5084
url: /th/aspose.slides/shape/
---
## คลาส Shape

แทนรูปทรงบนสไลด์.

```cpp
class Shape : public virtual Aspose::Slides::IShape,
              public Aspose::Slides::IDOMObject
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](./addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ถือว่า NaN สองค่ามีค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่ถือว่า NaN สองค่ามีค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| [System::String](../../system/string/) [get_AlternativeText](./get_alternativetext/)() override | คืนค่าข้อความแทนที่เชื่อมโยงกับรูปทรง อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_AlternativeTextTitle](./get_alternativetexttitle/)() override | คืนค่าชื่อเรื่องของข้อความแทนที่เชื่อมโยงกับรูปทรง อ่าน [System::String](../../system/string/) |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](./get_blackwhitemode/)() override | คุณสมบัติระบุว่ารูปทรงจะเรนเดอร์อย่างไรในโหมดแสดงผลสีขาว-ดำ.. อ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| **int32_t** [get_ConnectionSiteCount](./get_connectionsitecount/)() override | คืนค่าจำนวนจุดเชื่อมต่อบนรูปทรง อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | คืนค่าข้อมูลกำหนดเองของรูปทรง อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() override | คืนค่าอ็อบเจกต์ [EffectFormat](../effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์ อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() override | คืนค่าอ็อบเจกต์ [FillFormat](../fillformat/) ที่มีคุณสมบัติกำหนดรูปแบบการเติมสีสำหรับรูปทรง หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติการเติมสี อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](./get_frame/)() override | คืนค่าคุณสมบัติของกรอบรูปทรง อ่าน [IShapeFrame](../ishapeframe/) |
| **float** [get_Height](./get_height/)() override | รับความสูงของรูปทรง วัดเป็นจุด อ่าน **float** |
| **bool** [get_Hidden](./get_hidden/)() override | กำหนดว่ารูปทรงถูกซ่อนไว้หรือไม่ อ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](./get_hyperlinkclick/)() override | คืนค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการคลิกเมาส์ อ่าน [IHyperlink](../ihyperlink/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](./get_hyperlinkmanager/)() override | คืนค่าตัวจัดการลิงก์ไฮเปอร์ อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](./get_hyperlinkmouseover/)() override | คืนค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับเมาส์โอเวอร์ อ่าน [IHyperlink](../ihyperlink/) |
| **bool** [get_IsDecorative](./get_isdecorative/)() override | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| **bool** [get_IsGrouped](./get_isgrouped/)() override | กำหนดว่ารูปทรงเป็นกลุ่มหรือไม่ อ่านอย่างเดียว **bool** |
| **bool** [get_IsTextHolder](./get_istextholder/)() override | กำหนดว่ารูปทรงเป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() override | คืนค่าอ็อบเจกต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติกำหนดรูปแบบเส้นสำหรับรูปทรง หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติเส้น อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | คืนชื่อของรูปทรง ต้องไม่เป็น null ใช้ค่าว่างหากจำเป็น อ่าน [System::String](../../system/string/) |
| **uint32_t** [get_OfficeInteropShapeId](./get_officeinteropshapeid/)() override | คืนค่าตัวระบุเอกลักษณ์เฉพาะสไลด์ที่คงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงจากที่ใดก็ได้ในเอกสารได้อย่างเชื่อถือได้ อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_UniqueId](./get_uniqueid/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() override | คืนอ็อบเจกต์แม่แบบ [GroupShape](../groupshape/) หากรูปทรงอยู่ในกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](./get_placeholder/)() override | คืนค่า placeholder สำหรับรูปทรง คืนค่า null หากรูปทรงไม่มี placeholder อ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | คืนการนำเสนอแม่ของสไลด์ อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](./get_rawframe/)() override | คืนคุณสมบัติของกรอบรูปทรงดิบ อ่าน [IShapeFrame](../ishapeframe/) |
| **float** [get_Rotation](./get_rotation/)() override | คืนค่าจำนวนองศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา อ่าน **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](./get_shapelock/)() override | คืนค่าการล็อกของรูปทรง อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](./get_slide/)() override | คืนสไลด์แม่ของรูปทรง อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() override | คืนค่าอ็อบเจกต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติเพิ่มมิติ 3 มิติสำหรับรูปทรง หมายเหตุ: สามารถคืนค่า null สำหรับรูปทรงบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| **uint32_t** [get_UniqueId](./get_uniqueid/)() override | คืนค่าตัวระบุภายในที่มีขอบเขตระดับการนำเสนอซึ่งออกแบบสำหรับใช้งานโดยส่วนเสริมหรือโค้ดอื่น เนื่องจากค่านี้สามารถได้รับการกำหนดใหม่โดยผู้ใช้หรือโปรแกรมได้ จึงไม่ควรถือเป็นคีย์เอกลักษณ์ถาวร อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [Shape::get_OfficeInteropShapeId](./get_officeinteropshapeid/) |
| **float** [get_Width](./get_width/)() override | รับความกว้างของรูปทรง วัดเป็นจุด อ่าน **float** |
| **float** [get_X](./get_x/)() override | รับพิกัด x ของมุมซ้ายบนของรูปทรง วัดเป็นจุด อ่าน **float** |
| **float** [get_Y](./get_y/)() override | รับพิกัด y ของมุมซ้ายบนของรูปทรง วัดเป็นจุด อ่าน **float** |
| **int32_t** [get_ZOrderPosition](./get_zorderposition/)() override | คืนค่าตำแหน่งของรูปทรงในลำดับ z Shapes[0] คืนรูปทรงที่อยู่ด้านหลังของลำดับ z และ Shapes[Shapes.Count - 1] คืนรูปทรงที่อยู่ด้านหน้า อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](./getbaseplaceholder/)() override | คืนรูปทรง placeholder พื้นฐาน (รูปทรงจากเลย์เอาต์และ/หรือสไลด์หลักที่รูปทรงปัจจุบันสืบทอดมา) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจกต์กำหนดเองได้ |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() override | คืน thumbnail ของรูปทรง [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ประเภทขอบเขต thumbnail ของรูปทรงจะใช้เป็นค่าเริ่มต้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | คืน thumbnail ของรูปทรง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์ เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](./getvisualbounds/)() | รับขอบเขตภาพของรูปทรงที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType เป็นอเนกประสงค์ของตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทกำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และทำให้สามารถคัดลอกสร้างซับคลาสได้ |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และทำให้สามารถคัดลอกสร้างซับคลาสได้ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจกต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | พิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | พิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [RemovePlaceholder](./removeplaceholder/)() override | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder |
| void [set_AlternativeText](./set_alternativetext/)([System::String](../../system/string/)) override | ตั้งค่าข้อความแทนที่เชื่อมโยงกับรูปทรง เขียน [System::String](../../system/string/) |
| void [set_AlternativeTextTitle](./set_alternativetexttitle/)([System::String](../../system/string/)) override | ตั้งชื่อเรื่องของข้อความแทนที่เชื่อมโยงกับรูปทรง เขียน [System::String](../../system/string/) |
| void [set_BlackWhiteMode](./set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | คุณสมบัติกำหนดว่ารูปทรงจะเรนเดอร์อย่างไรในโหมดแสดงผลสีขาว-ดำ.. เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| void [set_Frame](./set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของกรอบรูปทรง เขียน [IShapeFrame](../ishapeframe/) |
| void [set_Height](./set_height/)(**float**) override | ตั้งค่าความสูงของรูปทรง วัดเป็นจุด เขียน **float** |
| void [set_Hidden](./set_hidden/)(**bool**) override | กำหนดว่ารูปทรงถูกซ่อนไว้หรือไม่ เขียน **bool** |
| void [set_HyperlinkClick](./set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการคลิกเมาส์ เขียน [IHyperlink](../ihyperlink/) |
| void [set_HyperlinkMouseOver](./set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับเมาส์โอเวอร์ เขียน [IHyperlink](../ihyperlink/) |
| void [set_IsDecorative](./set_isdecorative/)(**bool**) override | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | ตั้งค่าชื่อของรูปทรง ต้องไม่เป็น null ใช้ค่าว่างหากต้องการ เขียน [System::String](../../system/string/) |
| void [set_RawFrame](./set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของกรอบรูปทรงดิบ เขียน [IShapeFrame](../ishapeframe/) |
| void [set_Rotation](./set_rotation/)(**float**) override | ตั้งค่าจำนวนองศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา เขียน **float** |
| void [set_Width](./set_width/)(**float**) override | ตั้งค่าความกว้างของรูปทรง วัดเป็นจุด เขียน **float** |
| void [set_X](./set_x/)(**float**) override | ตั้งค่าพิกัด x ของมุมซ้ายบนของรูปทรง วัดเป็นจุด เขียน **float** |
| void [set_Y](./set_y/)(**float**) override | ตั้งค่าพิกัด y ของมุมซ้ายบนของรูปทรง วัดเป็นจุด เขียน **float** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared) อนุญาตให้สลับ pointer ใน container เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับการอ้างอิงที่แชร์และคืนค่า ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจกต์กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการทำงานของ C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหาของ [Shape](./) เป็นไฟล์ SVG |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | บันทึกเนื้อหาของ [Shape](./) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IShape](../ishape/)
* คลาส [IDOMObject](../idomobject/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)