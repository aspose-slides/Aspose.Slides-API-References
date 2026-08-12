---
title: IShape
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แสดงถึงรูปร่างบนสไลด์หนึ่ง
type: docs
weight: 3641
url: /th/aspose.slides/ishape/
---
## IShape คลาส

Represents a shape on a slide.

```cpp
class IShape : public virtual Aspose::Slides::ISlideComponent,
               public Aspose::Slides::IHyperlinkContainer
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](./addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติตัวแทนเป็นค่าที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในรูปแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่โดยที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# ที่โดยที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual [System::String](../../system/string/) [get_AlternativeText](./get_alternativetext/)() | คืนค่าข้อความทางเลือกที่เชื่อมโยงกับรูปทรง อ่าน [System::String](../../system/string/) |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](./get_alternativetexttitle/)() | คืนค่าชื่อเรื่องของข้อความทางเลือกที่เชื่อมโยงกับรูปทรง อ่าน [System::String](../../system/string/) |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](./get_blackwhitemode/)() | คุณสมบัติกำหนดว่ารูปทรงจะถูกแสดงอย่างไรในโหมดแสดงผลสีขาว-ดำ.. อ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| virtual **int32_t** [get_ConnectionSiteCount](./get_connectionsitecount/)() | คืนค่าจำนวนจุดเชื่อมต่อบนรูปทรง อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() | คืนค่าข้อมูลกำหนดเองของรูปทรง อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](./get_effectformat/)() | คืนค่าอ็อบเจ็กต์ [EffectFormat](../effectformat/) ที่มีเอฟเฟกต์พิกเซลที่ใช้กับรูปทรง อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](./get_fillformat/)() | คืนค่าอ็อบเจ็กต์ [FillFormat](../fillformat/) ที่มีคุณสมบัติการจัดรูปแบบเติมสำหรับรูปทรง อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](./get_frame/)() | คืนค่าคุณสมบัติของเฟรมรูปทรง อ่าน [IShapeFrame](../ishapeframe/) |
| virtual **float** [get_Height](./get_height/)() | รับความสูงของรูปทรง หน่วยเป็นจุด อ่าน **float** |
| virtual **bool** [get_Hidden](./get_hidden/)() | ตรวจสอบว่ารูปทรงถูกซ่อนหรือไม่ อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | คืนค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการคลิกเมาส์ อ่าน [IHyperlink](../ihyperlink/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ผู้จัดการลิงก์ไฮเปอร์ อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | คืนค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการชี้เมาส์ อ่าน [IHyperlink](../ihyperlink/) |
| virtual **bool** [get_IsDecorative](./get_isdecorative/)() | รับตัวเลือก 'ทำเครื่องหมายเป็นการตกแต่ง' อ่าน/เขียน **bool** |
| virtual **bool** [get_IsGrouped](./get_isgrouped/)() | ตรวจสอบว่ารูปทรงถูกรวมกลุ่มหรือไม่ อ่านอย่างเดียว **bool** |
| virtual **bool** [get_IsTextHolder](./get_istextholder/)() | ตรวจสอบว่ารูปทรงเป็น TextHolder หรือไม่ อ่านอย่างเดียว **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](./get_lineformat/)() | คืนค่าอ็อบเจ็กต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| virtual [System::String](../../system/string/) [get_Name](./get_name/)() | คืนชื่อของรูปทรง อ่าน [System::String](../../system/string/) |
| virtual **uint32_t** [get_OfficeInteropShapeId](./get_officeinteropshapeid/)() | คืนค่าตัวระบุที่ไม่ซ้ำซึ่งมีขอบเขตระดับสไลด์ซึ่งคงที่ตลอดอายุของรูปทรงและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปทรงได้อย่างเชื่อถือจากทุกตำแหน่งในเอกสาร อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_UniqueId](./get_uniqueid/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](./get_parentgroup/)() | คืนค่าอ็อบเจ็กต์ [GroupShape](../groupshape/) พาเรนท์หากรูปทรงถูกรวมกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](./get_placeholder/)() | คืนตัวแทนในรูปทรง อ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | คืนการนำเสนอ อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](./get_rawframe/)() | คืนค่าคุณสมบัติของเฟรมรูปทรงดิบ อ่าน [IShapeFrame](../ishapeframe/) |
| virtual **float** [get_Rotation](./get_rotation/)() | คืนค่ามาตราวางของการหมุนของรูปทรงที่ระบุรอบแกน z เป็นหน่วยองศา ค่าบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา อ่าน **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](./get_shapelock/)() | คืนค่าการล็อกของรูปทรง อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | คืนสไลด์พื้นฐาน อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](./get_threedformat/)() | คืนค่าอ็อบเจ็กต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปทรง อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| virtual **uint32_t** [get_UniqueId](./get_uniqueid/)() | คืนค่าตัวระบุภายในที่มีขอบเขตระดับการนำเสนอซึ่งตั้งใจให้ส่วนเสริมหรือโค้ดอื่นใช้ เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม จึงไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร อ่านอย่างเดียว **uint32_t**. ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](./get_officeinteropshapeid/) |
| virtual **float** [get_Width](./get_width/)() | รับความกว้างของรูปทรง หน่วยเป็นจุด อ่าน **float** |
| virtual **float** [get_X](./get_x/)() | รับพิกัด x ของมุมซ้ายบนของรูปทรง หน่วยเป็นจุด อ่าน **float** |
| virtual **float** [get_Y](./get_y/)() | รับพิกัด y ของมุมซ้ายบนของรูปทรง หน่วยเป็นจุด อ่าน **float** |
| virtual **int32_t** [get_ZOrderPosition](./get_zorderposition/)() | คืนค่าตำแหน่งของรูปทรงในลำดับ z Shapes[0] คืนรูปทรงที่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปทรงที่ด้านหน้า ของลำดับ z อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](./)\> [GetBasePlaceholder](./getbaseplaceholder/)() | คืนค่ารูปทรงตัวแทนพื้นฐาน (รูปทรงจากเค้าโครงและ/หรือสไลด์แม่ที่รูปทรงปัจจุบันสืบทอดมาจาก) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เหมือนเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์กำหนดเองได้ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() | คืนรูปย่อของรูปทรง [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ชนิดขอบเขตรูปย่อของรูปทรงจะใช้เป็นค่าเริ่มต้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | คืนรูปย่อของรูปทรง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เหมือนการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เหมือนตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำล๊อค. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เหมือนเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทกำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกคอนสตรัคเตอร์ของซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่ใช้ร่วมกันโดยค่าที่ระบุ |
| virtual void [RemovePlaceholder](./removeplaceholder/)() | กำหนดว่ารูปทรงนี้ไม่ใช่ placeholder |
| virtual void [set_AlternativeText](./set_alternativetext/)([System::String](../../system/string/)) | ตั้งค่าข้อความทางเลือกที่เชื่อมโยงกับรูปทรง เขียน [System::String](../../system/string/) |
| virtual void [set_AlternativeTextTitle](./set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งชื่อเรื่องของข้อความทางเลือกที่เชื่อมโยงกับรูปทรง เขียน [System::String](../../system/string/) |
| virtual void [set_BlackWhiteMode](./set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | คุณสมบัติกำหนดว่ารูปทรงจะถูกแสดงอย่างไรในโหมดสีขาว-ดำ.. เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| virtual void [set_Frame](./set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของเฟรมรูปทรง เขียน [IShapeFrame](../ishapeframe/) |
| virtual void [set_Height](./set_height/)(**float**) | ตั้งค่าความสูงของรูปทรง หน่วยเป็นจุด เขียน **float** |
| virtual void [set_Hidden](./set_hidden/)(**bool**) | กำหนดว่ารูปทรงถูกซ่อนหรือไม่ เขียน **bool** |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการคลิกเมาส์ เขียน [IHyperlink](../ihyperlink/) |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งค่าลิงก์ไฮเปอร์ที่กำหนดสำหรับการชี้เมาส์ เขียน [IHyperlink](../ihyperlink/) |
| virtual void [set_IsDecorative](./set_isdecorative/)(**bool**) | ตั้งค่าตัวเลือก 'ทำเครื่องหมายเป็นการตกแต่ง' อ่าน/เขียน **bool** |
| virtual void [set_Name](./set_name/)([System::String](../../system/string/)) | ตั้งชื่อของรูปทรง เขียน [System::String](../../system/string/) |
| virtual void [set_RawFrame](./set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของเฟรมรูปทรงดิบ เขียน [IShapeFrame](../ishapeframe/) |
| virtual void [set_Rotation](./set_rotation/)(**float**) | ตั้งค่ามาตราวางของการหมุนของรูปทรงที่ระบุรอบแกน z เป็นหน่วยองศา ค่าบวกแสดงการหมุนตามเข็มนาฬิกา; ค่าลบแสดงการหมุนทวนเข็มนาฬิกา เขียน **float** |
| virtual void [set_Width](./set_width/)(**float**) | ตั้งค่าความกว้างของรูปทรง หน่วยเป็นจุด เขียน **float** |
| virtual void [set_X](./set_x/)(**float**) | ตั้งค่าพิกัด x ของมุมซ้ายบนของรูปทรง หน่วยเป็นจุด เขียน **float** |
| virtual void [set_Y](./set_y/)(**float**) | ตั้งค่าพิกัด y ของมุมซ้ายบนของรูปทรง หน่วยเป็นจุด เขียน **float** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เหมือนเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentry [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนที่ใช้ smart pointers หรือ ThisProtector |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [ISlideComponent](../islidecomponent/)
* คลาส [IHyperlinkContainer](../ihyperlinkcontainer/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)