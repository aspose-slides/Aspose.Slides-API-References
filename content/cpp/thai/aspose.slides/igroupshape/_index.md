---
title: IGroupShape
second_title: Aspose.Slides สำหรับ C++ คู่มืออ้างอิง API
description: แสดงกลุ่มของรูปร่างบนสไลด์.
type: docs
weight: 2484
url: /th/aspose.slides/igroupshape/
---
## IGroupShape คลาส

แสดงถึงกลุ่มของรูปร่างบนสไลด์.

```cpp
class IGroupShape : public virtual Aspose::Slides::IShape
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ floating point แบบ C# ซึ่ง NaN สองค่าให้ถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขแบบ floating point แบบ C# ซึ่ง NaN สองค่าให้ถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | ส่งคืนข้อความทางเลือกที่เชื่อมโยงกับรูปร่าง. อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | ส่งคืนชื่อของข้อความทางเลือกที่เชื่อมโยงกับรูปร่าง. อ่าน [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | คุณสมบัตินี้ระบุว่ารูปร่างจะถูกแสดงอย่างไรในโหมดสีดำ-ขาว. อ่าน [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | ส่งคืนจำนวนจุดเชื่อมต่อบนรูปร่าง. อ่านอย่างเดียว **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | ส่งคืนข้อมูลแบบกำหนดเองของรูปร่าง. อ่านอย่างเดียว [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | ส่งคืนอ็อบเจกต์ [EffectFormat](../effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง. อ่านอย่างเดียว [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | ส่งคืนอ็อบเจกต์ [FillFormat](../fillformat/) ที่มีคุณสมบัติการจัดรูปแบบการเติมสำหรับรูปร่าง. อ่านอย่างเดียว [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | ส่งคืนคุณสมบัติของเฟรมรูปร่าง. อ่าน [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShapeLock](../igroupshapelock/)\> [get_GroupShapeLock](./get_groupshapelock/)() | ส่งคืนการล็อคของรูปร่าง. อ่านอย่างเดียว [IGroupShapeLock](../igroupshapelock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | รับความสูงของรูปร่างที่วัดเป็นจุด. อ่าน **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | ส่งคืนไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. อ่าน [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ผู้จัดการไฮเปอร์ลิงก์ อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | ส่งคืนไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ. อ่าน [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | กำหนดว่ารูปร่างเป็น TextHolder หรือไม่. อ่านอย่างเดียว **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | ส่งคืนอ็อบเจกต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. อ่านอย่างเดียว [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | ส่งคืนชื่อของรูปร่าง. อ่าน [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | ส่งคืนตัวระบุที่ไม่ซ้ำกันระดับสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างจากที่ใดก็ได้ในเอกสารได้อย่างเชื่อถือได้. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](./)\> [get_ParentGroup](../ishape/get_parentgroup/)() | ส่งคืนอ็อบเจกต์พาเรนท์ [GroupShape](../groupshape/) หากรูปร่างอยู่ในกลุ่ม มิฉะนั้นส่งคืน null. อ่านอย่างเดียว [IGroupShape](./). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | ส่งคืน placeholder ของรูปร่าง. อ่านอย่างเดียว [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | ส่งคืนการนำเสนอ. อ่านอย่างเดียว [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | ส่งคืนคุณสมบัติของเฟรมรูปร่างแบบดิบ. อ่าน [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | ส่งคืนจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา. อ่าน **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)(**int32_t**) | ส่งคืนรูปร่างภายในกลุ่มที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [Aspose::Slides::IShape](../ishape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | ส่งคืนการล็อคของรูปร่าง. อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](./get_shapes/)() | ส่งคืนคอลเลกชันของรูปร่างภายในกลุ่ม. อ่านอย่างเดียว [IShapeCollection](../ishapecollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | ส่งคืนสไลด์พื้นฐาน. อ่านอย่างเดียว [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | ส่งคืนอ็อบเจกต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง. อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | ส่งคืนตัวระบุภายในระดับการนำเสนอที่ออกแบบให้ใช้โดย add-in หรือโค้ดอื่น เนื่องจากค่า nàyอาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม ดังนั้นจึงไม่ควรใช้เป็นคีย์ที่คงที่อย่างถาวร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | รับความกว้างของรูปร่างที่วัดเป็นจุด. อ่าน **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | รับพิกัด x ของมุมซ้ายบนของรูปร่างที่วัดเป็นจุด. อ่าน **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | รับพิกัด y ของมุมซ้ายบนของรูปร่างที่วัดเป็นจุด. อ่าน **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | ส่งคืนตำแหน่งของรูปร่างในลำดับ z Shapes[0] ส่งคืนรูปร่างที่อยู่ด้านหลังของลำดับ z และ Shapes[Shapes.Count - 1] ส่งคืนรูปร่างที่อยู่ด้านหน้าของลำดับ z. อ่านอย่างเดียว **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | ส่งคืนรูปร่าง placeholder พื้นฐาน (รูปร่างจากเลย์เอาท์และ/หรือสไลด์หลักที่รูปร่างปัจจุบันสืบทอดมา). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อันแสดงคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจกต์กำหนดเอง. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | ส่งคืน shape thumbnail. [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ประเภทขอบเขตของ shape thumbnail จะถูกใช้เป็นค่าเริ่มต้น. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | ส่งคืน shape thumbnail. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาประเภทกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆ แล้วไม่ได้คัดลอกรายการใดๆ เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสำหรับคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมายค่า. จริงๆ แล้วไม่ได้คัดลอกรายการใดๆ เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสำหรับคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่ากับ nullptr โดยอ้างอิง. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำ specialize ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำ specialize ของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | ตั้งค่าข้อความทางเลือกที่เชื่อมโยงกับรูปร่าง. เขียน [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งค่าชื่อของข้อความทางเลือกที่เชื่อมโยงกับรูปร่าง. เขียน [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | กำหนดว่ารูปร่างจะถูกแสดงในโหมดสีดำ-ขาวอย่างไร. เขียน [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของเฟรมรูปร่าง. เขียน [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ตั้งค่าความสูงของรูปร่างที่วัดเป็นจุด. เขียน **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | กำหนดว่ารูปร่างถูกซ่อนหรือไม่. เขียน **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์. เขียน [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ. เขียน [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | ตั้งชื่อของรูปร่าง. เขียน [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของเฟรมรูปร่างแบบดิบ. เขียน [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | ตั้งค่าจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา. เขียน **float**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | ตั้งค่าความกว้างของรูปร่างที่วัดเป็นจุด. เขียน **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | ตั้งค่าพิกัด x ของมุมซ้ายบนของรูปร่างที่วัดเป็นจุด. เขียน **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | ตั้งค่าพิกัด y ของมุมซ้ายบนของรูปร่างที่วัดเป็นจุด. เขียน **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (ไม่ใช่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการจำลองโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหา [Shape](../shape/) เป็นไฟล์ SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหา [Shape](../shape/) เป็นไฟล์ SVG. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IShape](../ishape/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)