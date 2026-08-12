---
title: ZoomFrame
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แทนวัตถุ Slide Zoom ในสไลด์หนึ่ง
type: docs
weight: 5578
url: /th/aspose.slides/zoomframe/
---
## ZoomFrame คลาส

แทนวัตถุ [Slide](../slide/) Zoom ในสไลด์หนึ่ง.

```cpp
class ZoomFrame : public Aspose::Slides::ZoomObject,
                  public Aspose::Slides::IZoomFrame
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | เพิ่ม placeholder ใหม่หากไม่มีและตั้งค่าคุณสมบัติของ placeholder ให้เป็นค่าที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในรูปแบบ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าตัวเลขแบบลอยจุดสไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าตัวเลขแบบลอยจุดสไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับภายในเท่านั้น |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | คืนข้อความทางเลือกที่สัมพันธ์กับรูปร่าง อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | คืนชื่อเรื่องของข้อความทางเลือกที่สัมพันธ์กับรูปร่าง อ่าน [System::String](../../system/string/) |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | คุณสมบัติกำหนดว่ารูปร่างจะเรนเดอร์ในโหมดแสดงผลขาว-ดำอย่างไร อ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | คืนจำนวนจุดเชื่อมต่อบนรูปร่าง อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | คืนข้อมูลกำหนดเองของรูปร่าง อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | คืนอ็อบเจ็กต์ [EffectFormat](../effectformat/) ที่บรรจุเอฟเฟ็กต์พิกเซลที่ใช้กับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติเอฟเฟ็กต์ อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | คืนอ็อบเจ็กต์ [FillFormat](../fillformat/) ที่บรรจุคุณสมบัติกำหนดรูปแบบการเติมสำหรับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติการเติม อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | คืนคุณสมบัติของกรอบรูปร่าง อ่าน [IShapeFrame](../ishapeframe/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | คืนการล็อคของรูปร่าง อ่านอย่างเดียว [IGraphicalObjectLock](../igraphicalobjectlock/) |
| **float** [get_Height](../shape/get_height/)() override | รับความสูงของรูปร่างที่วัดเป็นจุด อ่าน **float** |
| **bool** [get_Hidden](../shape/get_hidden/)() override | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ อ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | คืนไฮเปอร์ลิงก์ที่กำหนดไว้สำหรับการคลิกเมาส์ อ่าน [IHyperlink](../ihyperlink/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | คืนตัวจัดการไฮเปอร์ลิงก์ อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | คืนไฮเปอร์ลิงก์ที่กำหนดไว้สำหรับเมาส์อยู่เหนือ อ่าน [IHyperlink](../ihyperlink/) |
| [ZoomImageType](../zoomimagetype/) [get_ImageType](../zoomobject/get_imagetype/)() override | รับประเภทภาพของวัตถุ zoom อ่าน [ZoomImageType](../zoomimagetype/) ค่าเริ่มต้น: Preview |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | กำหนดว่ารูปร่างอยู่ในกลุ่มหรือไม่ อ่านอย่างเดียว **bool** |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | คืนอ็อบเจ็กต์ [LineFormat](../lineformat/) ที่บรรจุคุณสมบัติกำหนดรูปแบบเส้นสำหรับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติเส้น อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | คืนชื่อของรูปร่าง ต้องไม่เป็น null ใช้ค่าสตริงว่างหากจำเป็น อ่าน [System::String](../../system/string/) |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | คืนรหัสประจำตัวที่ไม่ซ้ำกันแบบสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop อ้างอิงรูปร่างได้อย่างเชื่อถือจากทุกที่ในเอกสาร อ่านอย่างเดียว **uint32_t** ดูเพิ่มเติม [Shape::get_UniqueId](../shape/get_uniqueid/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | คืนอ็อบเจ็กต์ [GroupShape](../groupshape/) พ่อแม่หากรูปร่างอยู่ในกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | คืน placeholder สำหรับรูปร่าง คืนค่า null หากรูปร่างไม่มี placeholder อ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | คืนการนำเสนอพาเรนต์ของสไลด์ อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | คืนคุณสมบัติของกรอบรูปร่างดิบ อ่าน [IShapeFrame](../ishapeframe/) |
| **bool** [get_ReturnToParent](../zoomobject/get_returntoparent/)() override | รับพฤติกรรมการนำทางในการนำเสนอ อ่าน **bool** ค่าเริ่มต้น: false |
| **float** [get_Rotation](../shape/get_rotation/)() override | คืนจำนวนองศาที่รูปร่างระบุถูกหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา ค่าเป็นลบแสดงการหมุนต้านเข็มนาฬิกา อ่าน **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | คืนการล็อคของรูปร่าง อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| **bool** [get_ShowBackground](../zoomobject/get_showbackground/)() override | รับค่าที่ระบุกำหนดว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่ อ่าน **bool** ค่าเริ่มต้น: true |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | คืนสไลด์พาเรนต์ของรูปร่าง อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_TargetSlide](./get_targetslide/)() override | รับอ็อบเจ็กต์สไลด์ที่วัตถุ Zoom [Slide](../slide/) เชื่อมโยงไปอ่าน [ISlide](../islide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | คืนอ็อบเจ็กต์ [ThreeDFormat](../threedformat/) ที่บรรจุคุณสมบัติเอฟเฟ็กต์ 3 มิติสำหรับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปแบบบางประเภทที่ไม่มีคุณสมบัติ 3 มิติ อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| **float** [get_TransitionDuration](../zoomobject/get_transitionduration/)() override | รับระยะเวลาการเปลี่ยนระหว่าง Zoom และสไลด์ อ่าน **float** ค่าเริ่มต้น: 1.0f |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | คืนรหัสประจำตัวภายในแบบผูกกับการนำเสนอที่ออกแบบสำหรับใช้โดย add-in หรือโค้ดอื่น เนื่องจากค่านี้อาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม ต้องไม่ถือเป็นคีย์ที่คงที่ อ่านอย่างเดียว **uint32_t** ดูเพิ่มเติม [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/) |
| **float** [get_Width](../shape/get_width/)() override | รับความกว้างของรูปร่างที่วัดเป็นจุด อ่าน **float** |
| **float** [get_X](../shape/get_x/)() override | รับพิกัด x ของมุมบนซ้ายของรูปร่างที่วัดเป็นจุด อ่าน **float** |
| **float** [get_Y](../shape/get_y/)() override | รับพิกัด y ของมุมบนซ้ายของรูปร่างที่วัดเป็นจุด อ่าน **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../zoomobject/get_zoomimage/)() override | รับภาพสำหรับวัตถุ zoom อ่าน [IPPImage](../ippimage/) |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | คืนตำแหน่งของรูปร่างในลำดับ z Shapes[0] คืนรูปร่างที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าของลำดับ z อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | คืนรูปร่าง placeholder พื้นฐาน (รูปร่างจากเลเอาต์และ/หรือสไลด์มาสเตอร์ที่รูปร่างปัจจุบันสืบทอดมาจาก) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชวัตถุแบบกำหนดเองได้ |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | คืนภาพย่อของรูปร่าง [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ชนิดขอบเขตภาพย่อของรูปร่างใช้เป็นค่าเริ่มต้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | คืนภาพย่อของรูปร่าง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ เป็นอเนกประสงค์ของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | รับขอบเขตภาพของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType เป็นอเนกประสงค์ของตัวดำเนินการ C# 'is' |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถคล cloning ประเภทกำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้ซับคลาสคัดลอกได้ |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้ซับคลาสคัดลอกได้ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงกับอ็อบเจ็กต์ประเภทค่าโดยใช้ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงร่วมโดยค่าที่ระบุ |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | กำหนดว่ารูปร่างนี้ไม่ใช่ placeholder |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | ตั้งข้อความทางเลือกที่สัมพันธ์กับรูปร่าง เขียน [System::String](../../system/string/) |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | ตั้งชื่อเรื่องของข้อความทางเลือกที่สัมพันธ์กับรูปร่าง เขียน [System::String](../../system/string/) |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | คุณสมบัติกำหนดว่ารูปร่างจะเรนเดอร์ในโหมดแสดงผลขาว-ดำอย่างไร เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของกรอบรูปร่าง เขียน [IShapeFrame](../ishapeframe/) |
| void [set_Height](../shape/set_height/)(**float**) override | ตั้งค่าความสูงของรูปร่างที่วัดเป็นจุด เขียน **float** |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ เขียน **bool** |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับการคลิกเมาส์ เขียน [IHyperlink](../ihyperlink/) |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าไฮเปอร์ลิงก์ที่กำหนดสำหรับเมาส์อยู่เหนือ เขียน [IHyperlink](../ihyperlink/) |
| void [set_ImageType](../zoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) override | ตั้งประเภทภาพของวัตถุ zoom เขียน [ZoomImageType](../zoomimagetype/) ค่าเริ่มต้น: Preview |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | ตั้งตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | ตั้งชื่อของรูปร่าง ต้องไม่เป็น null ใช้ค่าว่างหากจำเป็น เขียน [System::String](../../system/string/) |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของกรอบรูปร่างดิบ เขียน [IShapeFrame](../ishapeframe/) |
| void [set_ReturnToParent](../zoomobject/set_returntoparent/)(**bool**) override | ตั้งพฤติกรรมการนำทางในสไลด์โชว์ เขียน **bool** ค่าเริ่มต้น: false |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | ตั้งจำนวนองศาที่รูปร่างระบุหมุนรอบแกน z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา ค่าลบแสดงการหมุนต้านเข็มนาฬิกา เขียน **float** |
| void [set_ShowBackground](../zoomobject/set_showbackground/)(**bool**) override | ตั้งค่าที่ระบุกำหนดว่า Zoom จะใช้พื้นหลังของสไลด์ปลายทางหรือไม่ เขียน **bool** ค่าเริ่มต้น: true |
| void [set_TargetSlide](./set_targetslide/)([System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>) override | ตั้งอ็อบเจ็กต์สไลด์ที่วัตถุ Zoom [Slide](../slide/) เชื่อมโยงไป เขียน [ISlide](../islide/) |
| void [set_TransitionDuration](../zoomobject/set_transitionduration/)(**float**) override | ตั้งระยะเวลาการเปลี่ยนระหว่าง Zoom และสไลด์ เขียน **float** ค่าเริ่มต้น: 1.0f |
| void [set_Width](../shape/set_width/)(**float**) override | ตั้งความกว้างของรูปร่างที่วัดเป็นจุด เขียน **float** |
| void [set_X](../shape/set_x/)(**float**) override | ตั้งพิกัด x ของมุมบนซ้ายของรูปร่างที่วัดเป็นจุด เขียน **float** |
| void [set_Y](../shape/set_y/)(**float**) override | ตั้งพิกัด y ของมุมบนซ้ายของรูปร่างที่วัดเป็นจุด เขียน **float** |
| void [set_ZoomImage](../zoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) override | ตั้งภาพสำหรับวัตถุ zoom เขียน [IPPImage](../ippimage/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทน shared) อนุญาตสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอเนกประสงค์ของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้แปลงวัตถุกำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิง weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิง weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [ZoomObject](../zoomobject/)
* คลาส [IZoomFrame](../izoomframe/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)