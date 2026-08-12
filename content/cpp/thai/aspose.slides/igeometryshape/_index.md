---
title: IGeometryShape
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แทนคลาสแม่สำหรับรูปทรงเรขาคณิตทั้งหมด.
type: docs
weight: 2354
url: /th/aspose.slides/igeometryshape/
---
## IGeometryShape คลาส


Represents the parent class for all geometric shapes.

```cpp
class IGeometryShape : public virtual Aspose::Slides::IShape
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | เพิ่มตัวครอบตำแหน่งใหม่หากไม่มีและตั้งค่าคุณสมบัติตัวครอบตำแหน่งเป็นค่าที่ระบุ |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](./createshapeelements/)() | สร้างและคืนค่าอาเรย์ขององค์ประกอบของรูปร่าง |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](./get_adjustment/)(**int32_t**) | คืนค่าการปรับแต่งของรูปร่างที่ตำแหน่งที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](./get_adjustments/)() | คืนคอลเลกชันของค่าการปรับแต่งของรูปร่าง อ่านอย่างเดียว [IAdjustValueCollection](../iadjustvaluecollection/) |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | คืนข้อความแสดงแทนที่สัมพันธ์กับรูปร่าง อ่าน [System::String](../../system/string/) |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | คืนชื่อเรื่องของข้อความแสดงแทนที่สัมพันธ์กับรูปร่าง อ่าน [System::String](../../system/string/) |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | คุณสมบัติระบุว่ารูปร่างจะเรนเดอร์อย่างไรในโหมดแสดงผลสีดำ-ขาว อ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | คืนจำนวนจุดเชื่อมต่อบนรูปร่าง อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | คืนข้อมูลกำหนดเองของรูปร่าง อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | คืนอ็อบเจ็กต์ [EffectFormat](../effectformat/) ที่มีเอฟเฟ็กต์พิกเซลที่ใช้กับรูปร่าง อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | คืนอ็อบเจ็กต์ [FillFormat](../fillformat/) ที่มีคุณสมบัติการจัดรูปแบบการเติมของรูปร่าง อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | คืนคุณสมบัติของกรอบรูปร่าง อ่าน [IShapeFrame](../ishapeframe/) |
| virtual **float** [get_Height](../ishape/get_height/)() | รับความสูงของรูปร่าง หน่วยเป็นพอยต์ อ่าน **float** |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | คืนไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์ อ่าน [IHyperlink](../ihyperlink/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ผู้จัดการไฮเปอร์ลิงก์ อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | คืนไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ อ่าน [IHyperlink](../ihyperlink/) |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | กำหนดว่ารูปร่างเป็นกลุ่มหรือไม่ อ่านอย่างเดียว **bool** |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | กำหนดว่ารูปร่างเป็น TextHolder หรือไม่ อ่านอย่างเดียว **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | คืนอ็อบเจ็กต์ [LineFormat](../lineformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | คืนชื่อของรูปร่าง อ่าน [System::String](../../system/string/) |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | คืนตัวระบุที่ไม่ซ้ำเฉพาะสไลด์ที่คงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้อย่างเชื่อถือจากที่ใดในเอกสารก็ได้ อ่านอย่างเดียว **uint32_t** ดูเพิ่มเติม [IShape::get_UniqueId](../ishape/get_uniqueid/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | คืนอ็อบเจ็กต์ [GroupShape](../groupshape/) พาเรนต์หากรูปร่างเป็นกลุ่ม มิฉะนั้นคืน null อ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | คืนตัวครอบตำแหน่งสำหรับรูปร่าง อ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | คืนการนำเสนอ อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | คืนคุณสมบัติของกรอบรูปร่างดิบ อ่าน [IShapeFrame](../ishapeframe/) |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | คืนจำนวนองศาที่รูปร่างที่ระบุหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา ค่าติดลบแสดงการหมุนทวนเข็มนาฬิกา อ่าน **float** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | คืนการล็อกของรูปร่าง อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](./get_shapestyle/)() | คืนอ็อบเจ็กต์สไตล์ของรูปร่าง อ่านอย่างเดียว [IShapeStyle](../ishapestyle/) |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](./get_shapetype/)() | คืนประเภทเทมเพลตเรขาคณิต หมายเหตุ: เมื่อเปลี่ยนค่า ค่าการปรับแต่งทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น อ่าน [Slides::ShapeType](../shapetype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | คืนสไลด์ฐาน อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | คืนอ็อบเจ็กต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | คืนตัวระบุภายในที่ใช้ในระดับการนำเสนอซึ่งตั้งใจให้ใช้งานโดย add-ins หรือโค้ดอื่น ๆ เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโดยโปรแกรม ควรไม่ถือเป็นคีย์ที่คงที่ อย่างเดียว อ่านอย่างเดียว **uint32_t** ดูเพิ่มเติม [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/) |
| virtual **float** [get_Width](../ishape/get_width/)() | รับความกว้างของรูปร่าง หน่วยเป็นพอยต์ อ่าน **float** |
| virtual **float** [get_X](../ishape/get_x/)() | รับพิกัด x ของมุมบนซ้ายของรูปร่าง หน่วยเป็นพอยต์ อ่าน **float** |
| virtual **float** [get_Y](../ishape/get_y/)() | รับพิกัด y ของมุมบนซ้ายของรูปร่าง หน่วยเป็นพอยต์ อ่าน **float** |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | คืนตำแหน่งของรูปร่างในลำดับ z Shapes[0] คืนรูปร่างที่อยู่ด้านหลังของลำดับ z และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าของลำดับ z อ่านอย่างเดียว **int32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | คืนรูปร่างตัวครอบตำแหน่งพื้นฐาน (รูปร่างจากเลย์เอาต์และ/หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอดมาจาก) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](./getgeometrypaths/)() | คืนสำเนาของเส้นทางของรูปร่างเรขาคณิต พิกัดสัมพันธ์กับมุมซ้ายบนของรูปร่าง |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) เปิดใช้งานการแฮชอ็อบเจ็กต์กำหนดเอง |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | คืนภาพย่อของรูปร่าง [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ประเภทขอบเขตภาพย่อของรูปร่างใช้เป็นค่าเริ่มต้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | คืนภาพย่อของรูปร่าง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์ อนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่ อนาล็อกของออปเรเตอร์ C# 'is' |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพล็กซ์ เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) เปิดใช้งานการโคลนประเภทกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา ไม่ได้คัดลอกสิ่งใดจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย ไม่ได้คัดลอกสิ่งใดจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบค่าประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะสำหรับ [Object::ReferenceEquals](../../system/object/referenceequals/) ในกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่ใช้ร่วมกันตามค่าที่ระบุ |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | กำหนดว่ารูปร่างนี้ไม่ใช่ตัวครอบตำแหน่ง |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | ตั้งข้อความแสดงแทนที่สัมพันธ์กับรูปร่าง เขียน [System::String](../../system/string/) |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | ตั้งชื่อเรื่องของข้อความแสดงแทนที่สัมพันธ์กับรูปร่าง เขียน [System::String](../../system/string/) |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | คุณสมบัติระบุว่ารูปร่างจะเรนเดอร์อย่างไรในโหมดแสดงผลสีดำ-ขาว เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของกรอบรูปร่าง เขียน [IShapeFrame](../ishapeframe/) |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ตั้งความสูงของรูปร่าง หน่วยเป็นพอยต์ เขียน **float** |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ เขียน **bool** |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์ เขียน [IHyperlink](../ihyperlink/) |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | ตั้งไฮเปอร์ลิงก์ที่กำหนดสำหรับการวางเมาส์เหนือ เขียน [IHyperlink](../ihyperlink/) |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | ตั้งตัวเลือก 'Mark as decorative' Reed/write **bool** |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | ตั้งชื่อของรูปร่าง เขียน [System::String](../../system/string/) |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | ตั้งค่าคุณสมบัติของกรอบรูปร่างดิบ เขียน [IShapeFrame](../ishapeframe/) |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | ตั้งจำนวนองศาที่รูปร่างที่ระบุหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา เขียน **float** |
| virtual void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | ตั้งประเภทเทมเพลตเรขาคณิต หมายเหตุ: เมื่อเปลี่ยนค่า ค่าการปรับแต่งทั้งหมดจะรีเซ็ตเป็นค่าเริ่มต้น เขียน [Slides::ShapeType](../shapetype/) |
| virtual void [set_Width](../ishape/set_width/)(**float**) | ตั้งความกว้างของรูปร่าง หน่วยเป็นพอยต์ เขียน **float** |
| virtual void [set_X](../ishape/set_x/)(**float**) | ตั้งพิกัด x ของมุมบนซ้ายของรูปร่าง หน่วยเป็นพอยต์ เขียน **float** |
| virtual void [set_Y](../ishape/set_y/)(**float**) | ตั้งพิกัด y ของมุมบนซ้ายของรูปร่าง หน่วยเป็นพอยต์ เขียน **float** |
| virtual void [SetGeometryPath](./setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | อัปเดตเรขาคณิตของรูปร่างจากอ็อบเจ็กต์ [IGeometryPath](../igeometrypath/) พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปร่าง เปลี่ยนประเภทของรูปร่าง ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/) |
| virtual void [SetGeometryPaths](./setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | อัปเดตเรขาคณิตของรูปร่างจากอาเรย์ของ [IGeometryPath](../igeometrypath/) พิกัดต้องสัมพันธ์กับมุมซ้ายบนของรูปร่าง เปลี่ยนประเภทของรูปร่าง ([ShapeType](../shapetype/)) เป็น [ShapeType::Custom](../shapetype/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทน shared) อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/) เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตาม construct typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# ปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IShape](../ishape/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)