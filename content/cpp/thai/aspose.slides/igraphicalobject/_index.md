---
title: IGraphicalObject
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: เป็นตัวแทนของวัตถุกราฟิกเชิงนามธรรม.
type: docs
weight: 2458
url: /th/aspose.slides/igraphicalobject/
---
## IGraphicalObject คลาส

แทนวัตถุกราฟิกเชิงนามธรรม.

```cpp
class IGraphicalObject : public virtual Aspose::Slides::IShape
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# โดยที่ NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# โดยที่ NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น. |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | คืนข้อความแทนที่เชื่อมโยงกับรูปทรง. อ่าน [System::String](../../system/string/). |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | คืนชื่อหัวข้อของข้อความแทนที่เชื่อมโยงกับรูปทรง. อ่าน [System::String](../../system/string/). |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | คุณสมบัติกำหนดว่ารูปทรงจะแสดงผลอย่างไรในโหมดแสดงผลขาว-ดำ. อ่าน [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | คืนจำนวนจุดเชื่อมต่อบนรูปทรง. อ่านอย่างเดียว **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | คืนข้อมูลกำหนดเองของรูปทรง. อ่านอย่างเดียว [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | คืนอ็อบเจกต์ [EffectFormat](../effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง. อ่านอย่างเดียว [IEffectFormat](../ieffectformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | คืนอ็อบเจกต์ [FillFormat](../fillformat/) ที่มีคุณสมบัติการจัดรูปแบบการเติมสีสำหรับรูปทรง. อ่านอย่างเดียว [IFillFormat](../ifillformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | คืนคุณสมบัติของเฟรมรูปทรง. อ่าน [IShapeFrame](../ishapeframe/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](./get_graphicalobjectlock/)() | คืนการล็อกของรูปทรง. อ่านอย่างเดียว [IGraphicalObjectLock](../igraphicalobjectlock/). |
| virtual **float** [get_Height](../ishape/get_height/)() | รับความสูงของรูปทรงเป็นหน่วยจุด. อ่าน **float**. |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | กำหนดว่ารูปทรงถูกซ่อนหรือไม่. อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | คืนไฮเปอร์ลิงก์ที่กำหนดสำหรับคลิกเมาส์. อ่าน [IHyperlink](../ihyperlink/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ผู้จัดการไฮเปอร์ลิงก์. อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | คืนไฮเปอร์ลิงก์ที่กำหนดสำหรับเมาส์วางเหนือ. อ่าน [IHyperlink](../ihyperlink/). |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool**. |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | กำหนดว่ารูปทรงเป็นกลุ่มหรือไม่. อ่านอย่างเดียว **bool**. |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | กำหนดว่ารูปทรงเป็น TextHolder หรือไม่. อ่านอย่างเดียว **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | คืนอ็อบเจกต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง. อ่านอย่างเดียว [ILineFormat](../ilineformat/). |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | คืนชื่อของรูปทรง. อ่าน [System::String](../../system/string/). |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | คืนตัวระบุที่ไม่ซ้ำเฉพาะสไลด์ซึ่งคงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงได้อย่างเชื่อถือจากทุกที่ในเอกสาร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_UniqueId](../ishape/get_uniqueid/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | คืนอ็อบเจกต์ [GroupShape](../groupshape/) พึ่งพาเมื่อรูปทรงอยู่ในกลุ่ม. มิฉะนั้นคืนค่า null. อ่านอย่างเดียว [IGroupShape](../igroupshape/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | คืน placeholder สำหรับรูปทรง. อ่านอย่างเดียว [IPlaceholder](../iplaceholder/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | คืนการนำเสนอ. อ่านอย่างเดียว [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | คืนคุณสมบัติของเฟรมรูปทรงดิบ. อ่าน [IShapeFrame](../ishapeframe/). |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | คืนจำนวนองศาที่รูปทรงที่ระบุหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. อ่าน **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | คืนการล็อกของรูปทรง. อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | คืนสไลด์ฐาน. อ่านอย่างเดียว [IBaseSlide](../ibaseslide/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | คืนอ็อบเจกต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง. อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/). |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | คืนตัวระบุภายในที่กำหนดตามการนำเสนอเพื่อใช้โดย add-in หรือโค้ดอื่น. เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม จึงไม่ควรถือเป็นคีย์ที่ไม่ซ้ำถาวร. อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/). |
| virtual **float** [get_Width](../ishape/get_width/)() | รับความกว้างของรูปทรงเป็นหน่วยจุด. อ่าน **float**. |
| virtual **float** [get_X](../ishape/get_x/)() | รับพิกัด x ของมุมบนซ้ายของรูปทรงเป็นหน่วยจุด. อ่าน **float**. |
| virtual **float** [get_Y](../ishape/get_y/)() | รับพิกัด y ของมุมบนซ้ายของรูปทรงเป็นหน่วยจุด. อ่าน **float**. |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | คืนตำแหน่งของรูปทรงในลำดับ z. Shapes[0] คืนรูปทรงที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปทรงที่อยู่ด้านหน้า. อ่านอย่างเดียว **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | คืนรูปทรง placeholder พื้นฐาน (รูปทรงจากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่รูปทรงปัจจุบันสืบทอดมา). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเมธอดที่คล้ายกับ C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจกต์กำหนดเอง. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | คืนภาพย่อของรูปทรง. โดยปกติใช้ประเภทขอบเขตภาพย่อ [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | คืนภาพย่อของรูปทรง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. คล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่ targetType ระบุ. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเมธอดที่คล้ายกับ C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคล cloning ประเภทกำหนดเอง. |
| [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกคอนสตรัคเตอร์ของคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงแบบแชร์ตามค่าที่ระบุ. |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder. |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | ตั้งค่าข้อความแทนที่เชื่อมโยงกับรูปทรง. เขียน [System::String](../../system/string/). |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งค่าชื่อหัวข้อของข้อความแทนที่เชื่อมโยงกับรูปทรง. เขียน [System::String](../../system/string/). |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | คุณสมบัติกำหนดว่ารูปทรงจะแสดงผลอย่างไรในโหมดแสดงผลขาว-ดำ. เขียน [Slides::BlackWhiteMode](../blackwhitemode/). |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของเฟรมรูปทรง. เขียน [IShapeFrame](../ishapeframe/). |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ตั้งค่าความสูงของรูปทรงเป็นหน่วยจุด. เขียน **float**. |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | กำหนดว่ารูปทรงถูกซ่อนหรือไม่. เขียน **bool**. |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับคลิกเมาส์. เขียน [IHyperlink](../ihyperlink/). |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับเมาส์วางเหนือ. เขียน [IHyperlink](../ihyperlink/). |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool**. |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | ตั้งชื่อของรูปทรง. เขียน [System::String](../../system/string/). |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของเฟรมรูปทรงดิบ. เขียน [IShapeFrame](../ishapeframe/). |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | ตั้งค่าจำนวนองศาที่รูปทรงที่ระบุหมุนรอบแกน z. ค่าบวกหมายถึงการหมุนตามเข็มนาฬิกา; ค่าลบหมายถึงการหมุนทวนเข็มนาฬิกา. เขียน **float**. |
| virtual void [set_Width](../ishape/set_width/)(**float**) | ตั้งค่าความกว้างของรูปทรงเป็นหน่วยจุด. เขียน **float**. |
| virtual void [set_X](../ishape/set_x/)(**float**) | ตั้งค่าพิกัด x ของมุมบนซ้ายของรูปทรงเป็นหน่วยจุด. เขียน **float**. |
| virtual void [set_Y](../ishape/set_y/)(**float**) | ตั้งค่าพิกัด y ของมุมบนซ้ายของรูปทรงเป็นหน่วยจุด. เขียน **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเท็มเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทนที่ shared). ให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงแบบแชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่า ตัวนับอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่าตัวนับอ้างอิงแบบแชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเมธอดที่คล้ายกับ C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหา [Shape](../shape/) เป็นไฟล์ SVG. |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหา [Shape](../shape/) เป็นไฟล์ SVG. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IShape](../ishape/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)