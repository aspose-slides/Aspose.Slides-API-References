---
title: ISectionZoomFrame
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนของอ็อบเจ็กต์ Section Zoom ในสไลด์.
type: docs
weight: 3602
url: /th/aspose.slides/isectionzoomframe/
---
## ISectionZoomFrame คลาส

Represents a [Section](../section/) Zoom object ในสไลด์.

```cpp
class ISectionZoomFrame : public virtual Aspose::Slides::IZoomObject
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบ floating point แบบ C# ที่ NaN สองค่าถูกพิจารณาว่าเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบ floating point แบบ C# ที่ NaN สองค่าถูกพิจารณาว่าเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อการภายในเท่านั้น |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | Returns the alternative text associated with a shape. Read [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | Returns the title of alternative text associated with a shape. Read [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | Property ระบุว่ารูปร่างจะเรนเดอร์ในโหมดแสดงผลสีขาว-ดำอย่างไร.. อ่าน [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | คืนค่าจำนวน connection sites ของ shape. แบบอ่านอย่างเดียว **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | คืนค่าข้อมูล custom ของ shape. แบบอ่านอย่างเดียว [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | คืนค่าอ็อบเจ็กต์ [EffectFormat](../effectformat/) ที่บรรจุ pixel effects ที่ใช้กับ shape. แบบอ่านอย่างเดียว [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | คืนค่าอ็อบเจ็กต์ [FillFormat](../fillformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบ fill สำหรับ shape. แบบอ่านอย่างเดียว [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | คืนค่าคุณสมบัติของ shape frame. อ่าน [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | คืนค่า locks ของ shape. แบบอ่านอย่างเดียว [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | รับค่าความสูงของ shape หน่วย points. อ่าน **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | กำหนดว่า shape ถูกซ่อนไปหรือไม่. อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | Returns the hyperlink defined for mouse click. Read [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | Hyperlinks manager แบบอ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | Returns the hyperlink defined for mouse over. Read [IHyperlink](../ihyperlink/). |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | รับประเภทภาพของ zoom object. อ่าน [ZoomImageType](../zoomimagetype/). ค่าเริ่มต้น: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | รับตัวเลือก 'Mark as decorative' แบบอ่าน/เขียน **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | กำหนดว่า shape อยู่ในกลุ่มหรือไม่. แบบอ่านอย่างเดียว **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | กำหนดว่า shape เป็น TextHolder หรือไม่. แบบอ่านอย่างเดียว **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | คืนค่าอ็อบเจ็กต์ [LineFormat](../lineformat/) ที่บรรจุคุณสมบัติการฟอร์แมตเส้นสำหรับ shape. แบบอ่านอย่างเดียว [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | Returns the name of a shape. Read [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | คืนค่า identifier แบบ unique ระดับสไลด์ที่คงที่ตลอดอายุของ shape และทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิง shape ได้จากทุกตำแหน่งในเอกสาร. แบบอ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | คืนค่าอ็อบเจ็กต์ parent [GroupShape](../groupshape/) หาก shape อยู่ในกลุ่ม มิฉะนั้นคืนค่า null. แบบอ่านอย่างเดียว [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | คืนค่า placeholder สำหรับ shape. แบบอ่านอย่างเดียว [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | Returns the presentation. Read-only [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | คืนค่าคุณสมบัติ raw shape frame. อ่าน [IShapeFrame](../ishapeframe/). |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | รับพฤติกรรมการนำทางใน slideshow. อ่าน **bool**. ค่าเริ่มต้น: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | คืนค่ามุมองศาที่ shape ถูกหมุนรอบแกน z. ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา. อ่าน **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | คืนค่า locks ของ shape. แบบอ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/). |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | รับค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่. อ่าน **bool**. ค่าเริ่มต้น: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | Returns the base slide. Read-only [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](./get_targetsection/)() | รับอ็อบเจ็กต์ section ที่อ็อบเจ็กต์ [Section](../section/) Zoom เชื่อมโยงอยู่. อ่าน [ISection](../isection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | คืนค่าอ็อบเจ็กต์ [ThreeDFormat](../threedformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบเส้นสำหรับ shape. แบบอ่านอย่างเดียว [IThreeDFormat](../ithreedformat/). |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | รับระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom และสไลด์. อ่าน **float**. ค่าเริ่มต้น: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | คืนค่า identifier ภายในระดับ presentation ที่ใช้โดย add-in หรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม, จึงไม่ควรถือเป็นคีย์ unique คงที่. แบบอ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | รับค่าความกว้างของ shape หน่วย points. อ่าน **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | รับค่า x-coordinate ของมุมซ้ายบนของ shape หน่วย points. อ่าน **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | รับค่า y-coordinate ของมุมซ้ายบนของ shape หน่วย points. อ่าน **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | รับภาพสำหรับ zoom object. อ่าน [IPPImage](../ippimage/). |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | คืนค่าตำแหน่งของ shape ใน z-order. Shapes[0] คืน shape ที่ตำแหน่งหลังสุดของ z-order, และ Shapes[Shapes.Count - 1] คืน shape ที่ตำแหน่งหน้าสุดของ z-order. แบบอ่านอย่างเดียว **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | คืนค่า shape placeholder พื้นฐาน (shape จาก layout และ/หรือ master slide ที่ shape ปัจจุบันสืบทอดมาจาก). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูล reference counter ที่เชื่อมกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเท่าเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจ็กต์แบบกำหนดเอง. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | Returns shape thumbnail. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) shape thumbnail bounds type is used by default. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | Returns shape thumbnail. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เทียบเท่าเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เทียบเท่าโอเปอร์เรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเท่าเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคล cloning ของประเภทกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไร, เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | อ็อปเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร, เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณี string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่า shared reference count ลงตามค่าที่ระบุ. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | กำหนดว่า shape นี้ไม่ใช่ placeholder. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | ตั้งค่า alternative text ที่เชื่อมกับ shape. เขียน [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งค่า title ของ alternative text ที่เชื่อมกับ shape. เขียน [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | Property ระบุวิธีที่ shape จะเรนเดอร์ในโหมดแสดงผลสีขาว-ดำ. เขียน [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของ shape frame. เขียน [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ตั้งค่าความสูงของ shape หน่วย points. เขียน **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | กำหนดว่า shape ซ่อนหรือไม่. เขียน **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่า hyperlink ที่กำหนดสำหรับการคลิกเมาส์. เขียน [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่า hyperlink ที่กำหนดสำหรับการเลื่อนเมาส์เหนือ. เขียน [IHyperlink](../ihyperlink/). |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | ตั้งค่าประเภทภาพของ zoom object. เขียน [ZoomImageType](../zoomimagetype/). ค่าเริ่มต้น: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ตั้งค่าตัวเลือก 'Mark as decorative' แบบอ่าน/เขียน **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | ตั้งค่าชื่อของ shape. เขียน [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติ raw shape frame. เขียน [IShapeFrame](../ishapeframe/). |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | ตั้งค่าพฤติกรรมการนำทางใน slideshow. เขียน **bool**. ค่าเริ่มต้น: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | ตั้งค่ามุมองศาที่ shape ถูกหมุนรอบแกน z. ค่าเป็นบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าเป็นลบหมายถึงการหมุนทวนเข็มนาฬิกา. เขียน **float**. |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | ตั้งค่าที่ระบุว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่. เขียน **bool**. ค่าเริ่มต้น: true |
| virtual void [set_TargetSection](./set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) | ตั้งค่าอ็อบเจ็กต์ section ที่อ็อบเจ็กต์ [Section](../section/) Zoom เชื่อมโยงอยู่. เขียน [ISection](../isection/). |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | ตั้งค่าระยะเวลาการเปลี่ยนผ่านระหว่าง Zoom และสไลด์. เขียน **float**. ค่าเริ่มต้น: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | ตั้งค่าความกว้างของ shape หน่วย points. เขียน **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | ตั้งค่า x-coordinate ของมุมซ้ายบนของ shape หน่วย points. เขียน **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | ตั้งค่า y-coordinate ของมุมซ้ายบนของ shape หน่วย points. เขียน **float**. |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | ตั้งค่าภาพสำหรับ zoom object. เขียน [IPPImage](../ippimage/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าตัวเทมเพลตที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของ shared reference counter. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่า shared reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่า shared reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเท่าเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็น string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่คล้าย C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกของ C# lock() statement. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่า weak reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่า weak reference count. ไม่ควรเรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IZoomObject](../izoomobject/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)