---
title: IInk
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงวัตถุหมึกบนสไลด์.
type: docs
weight: 1
url: /th/aspose.slides.ink/iink/
---
## IInk คลาส

แสดงถึงวัตถุหมึกบนสไลด์.

```cpp
class IInk : public virtual Aspose::Slides::IGraphicalObject
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุชนิดอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุชนิดค่าในรูปแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าได้รับการพิจารณาเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าได้รับการพิจารณาเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | ส่งคืนข้อความทางเลือกที่เชื่อมโยงกับรูปทรง อ่าน [System::String](../../system/string/) |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | ส่งคืนชื่อเรื่องของข้อความทางเลือกที่เชื่อมโยงกับรูปทรง อ่าน [System::String](../../system/string/) |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | คุณสมบัติกำหนดว่ารูปทรงจะถูกเรนเดอร์ในโหมดแสดงผลขาว-ดำอย่างไร .. อ่าน [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | ส่งคืนจำนวนจุดเชื่อมต่อบนรูปทรง อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | ส่งคืนข้อมูลที่กำหนดเองของรูปทรง อ่านอย่างเดียว [ICustomData](../../aspose.slides/icustomdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | ส่งคืนอ็อบเจกต์ [EffectFormat](../../aspose.slides/effectformat/) ที่มีผลพิกเซลที่ใช้กับรูปทรง อ่านอย่างเดียว [IEffectFormat](../../aspose.slides/ieffectformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | ส่งคืนอ็อบเจกต์ [FillFormat](../../aspose.slides/fillformat/) ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับรูปทรง อ่านอย่างเดียว [IFillFormat](../../aspose.slides/ifillformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | ส่งคืนคุณสมบัติของกรอบรูปทรง อ่าน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | ส่งคืนการล็อคของรูปทรง อ่านอย่างเดียว [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/) |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | รับความสูงของรูปทรง หน่วยเป็นพอยต์ อ่าน **float** |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | กำหนดว่ารูปทรงถูกซ่อนหรือไม่ อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | ส่งคืนไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์ อ่าน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | ผู้จัดการไฮเปอร์ลิงก์ อ่านอย่างเดียว [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | ส่งคืนไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ อ่าน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | กำหนดว่ารูปทรงเป็นกลุ่มหรือไม่ อ่านอย่างเดียว **bool** |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | กำหนดว่ารูปทรงเป็น TextHolder หรือไม่ อ่านอย่างเดียว **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | ส่งคืนอ็อบเจกต์ [LineFormat](../../aspose.slides/lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง อ่านอย่างเดียว [ILineFormat](../../aspose.slides/ilineformat/) |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | ส่งคืนชื่อของรูปทรง อ่าน [System::String](../../system/string/) |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | ส่งคืนตัวระบุที่เป็นเอกลักษณ์ในสไลด์ซึ่งคงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงจากตำแหน่งใดก็ได้ในเอกสารได้อย่างเชื่อถือได้ อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | ส่งคืนอ็อบเจกต์แม่ของ [GroupShape](../../aspose.slides/groupshape/) หากรูปทรงเป็นกลุ่ม มิฉะนั้นส่งคืน null อ่านอย่างเดียว [IGroupShape](../../aspose.slides/igroupshape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | ส่งคืน placeholder สำหรับรูปทรง อ่านอย่างเดียว [IPlaceholder](../../aspose.slides/iplaceholder/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | ส่งคืนการนำเสนอ อ่านอย่างเดียว [IPresentation](../../aspose.slides/ipresentation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | ส่งคืนคุณสมบัติของกรอบรูปทรงดิบ อ่าน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | ส่งคืนจำนวนองศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา ค่าเป็นลบแสดงการหมุนย้อนเข็มนาฬิกา อ่าน **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | ส่งคืนการล็อคของรูปทรง อ่านอย่างเดียว [IBaseShapeLock](../../aspose.slides/ibaseshapelock/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | ส่งคืนสไลด์ฐาน อ่านอย่างเดียว [IBaseSlide](../../aspose.slides/ibaseslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | ส่งคืนอ็อบเจกต์ [ThreeDFormat](../../aspose.slides/threedformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง อ่านอย่างเดียว [IThreeDFormat](../../aspose.slides/ithreedformat/) |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IInkTrace](../iinktrace/)\>\> [get_Traces](./get_traces/)() | รับทั้งหมดของ trace ที่อยู่ใน element [IInk](./) [IInkTrace](../iinktrace/). อ่านอย่างเดียว |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | ส่งคืนตัวระบุภายในที่ครอบคลุมการนำเสนอซึ่งออกแบบมาสำหรับใช้โดย add-in หรือโค้ดอื่น ๆ เนื่องจากค่าที่นี้อาจถูกรีแอสไ인โดยผู้ใช้หรือโปรแกรม จึงไม่ควรถือเป็นคีย์ที่คงที่แบบถาวร อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/) |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | รับความกว้างของรูปทรง หน่วยเป็นพอยต์ อ่าน **float** |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | รับค่า x-coordinate ของมุมบนซ้ายของรูปทรง หน่วยเป็นพอยต์ อ่าน **float** |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | รับค่า y-coordinate ของมุมบนซ้ายของรูปทรง หน่วยเป็นพอยต์ อ่าน **float** |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | ส่งคืนตำแหน่งของรูปทรงในลำดับ z Shapes[0] ส่งคืนรูปทรงที่อยู่ด้านหลังของลำดับ z และ Shapes[Shapes.Count - 1] ส่งคืนรูปทรงที่อยู่ด้านหน้าของลำดับ z อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | ส่งคืน placeholder shape พื้นฐาน (shape จาก layout หรือ master slide ที่ shape ปัจจุบันสืบทอดมาจาก) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจกต์ที่กำหนดเอง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | ส่งคืน thumbnail ของรูปทรง [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) ชนิดการกำหนดขอบ thumbnail ของรูปทรงจะถูกใช้เป็นค่าเริ่มต้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | ส่งคืน thumbnail ของรูปทรง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์ เทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType เทียบเคียงกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนนิ่งของประเภทที่กำหนดเอง |
| [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์มอบหมาย ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ชนิดค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | ตั้งข้อความทางเลือกที่เชื่อมโยงกับรูปทรง เขียน [System::String](../../system/string/) |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งชื่อเรื่องของข้อความทางเลือกที่เชื่อมโยงกับรูปทรง เขียน [System::String](../../system/string/) |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | คุณสมบัติกำหนดว่ารูปทรงจะถูกเรนเดอร์ในโหมดขาว-ดำอย่างไร .. เขียน [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | ตั้งค่าคุณสมบัติของกรอบรูปทรง เขียน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | ตั้งค่าความสูงของรูปทรง หน่วยเป็นพอยต์ เขียน **float** |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | กำหนดว่ารูปทรงถูกซ่อนหรือไม่ เขียน **bool** |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | ตั้งค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์ เขียน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | ตั้งค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ เขียน [IHyperlink](../../aspose.slides/ihyperlink/) |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | ตั้งค่าชื่อของรูปทรง เขียน [System::String](../../system/string/) |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | ตั้งค่าคุณสมบัติของกรอบรูปทรงดิบ เขียน [IShapeFrame](../../aspose.slides/ishapeframe/) |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | ตั้งค่าจำนวนองศาที่รูปทรงที่ระบุถูกหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา ค่าเป็นลบแสดงการหมุนย้อนเข็มนาฬิกา เขียน **float** |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | ตั้งค่าความกว้างของรูปทรง หน่วยเป็นพอยต์ เขียน **float** |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | ตั้งค่าค่า x-coordinate ของมุมบนซ้ายของรูปทรง หน่วยเป็นพอยต์ เขียน **float** |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | ตั้งค่าค่า y-coordinate ของมุมบนซ้ายของรูปทรง หน่วยเป็นพอยต์ เขียน **float** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared) อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งคืนตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ประมวลผล typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับ weak reference. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับ weak reference. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหาของ [Shape](../../aspose.slides/shape/) เป็นไฟล์ SVG |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหาของ [Shape](../../aspose.slides/shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* เนมสเปซ [Aspose::Slides::Ink](../)
* ไลบรารี [Aspose.Slides](../../)