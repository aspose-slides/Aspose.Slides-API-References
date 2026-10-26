---
title: OleObjectFrame
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงวัตถุ OLE บนสไลด์หนึ่ง
type: docs
weight: 4603
url: /th/aspose.slides/oleobjectframe/
---
## OleObjectFrame คลาส


แสดงถึงวัตถุ OLE บนสไลด์หนึ่ง.

```cpp
class OleObjectFrame : public Aspose::Slides::GraphicalObject,
                       public Aspose::Slides::IOleObjectFrame
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | เพิ่มตัวเติมใหม่หากไม่มีและตั้งค่าคุณสมบัติตัวเติมเป็นค่าที่ระบุ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อการภายในเท่านั้น |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | คืนค่าข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | คืนค่าชื่อเรื่องของข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง อ่าน [System::String](../../system/string/) |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | คุณสมบัติกำหนดว่ารูปร่างจะแสดงผลในโหมดสีขาว-ดำอย่างไร อ่าน [Slides::BlackWhiteMode](../blackwhitemode/) |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | คืนค่าจำนวนจุดเชื่อมต่อบนรูปร่าง อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | คืนค่าข้อมูลกำหนดเองของรูปร่าง อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | คืนค่าอ็อบเจ็กต์ [EffectFormat](../effectformat/) ที่บรรจุเอฟเฟกต์พิกเซลที่ใช้กับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเอฟเฟกต์ อ่านอย่างเดียว [IEffectFormat](../ieffectformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() override | รับข้อมูลเกี่ยวกับข้อมูลที่ฝังใน OLE อ่าน [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/) |
| [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() override | คืนค่าชื่อไฟล์ของวัตถุ OLE ที่ฝังไว้ |
| [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() override | คืนค่าที่อยู่ของวัตถุ OLE ที่ฝังไว้ |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | คืนค่าอ็อบเจ็กต์ [FillFormat](../fillformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบการเติมสีสำหรับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติการเติมสี อ่านอย่างเดียว [IFillFormat](../ifillformat/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | คืนค่าคุณสมบัติของเฟรมรูปร่าง อ่าน [IShapeFrame](../ishapeframe/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | คืนค่าการล็อคของรูปร่าง อ่านอย่างเดียว [IGraphicalObjectLock](../igraphicalobjectlock/) |
| **float** [get_Height](../shape/get_height/)() override | รับความสูงของรูปร่าง หน่วยเป็นพอยท์ อ่าน **float** |
| **bool** [get_Hidden](../shape/get_hidden/)() override | กำหนดว่ารูปร่างถูกซ่อนหรือไม่ อ่าน **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | คืนค่าการเชื่อมโยงที่กำหนดสำหรับคลิกเมาส์ อ่าน [IHyperlink](../ihyperlink/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | คืนผู้จัดการการเชื่อมโยง อ่านอย่างเดียว [IHyperlinkManager](../ihyperlinkmanager/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | คืนค่าการเชื่อมโยงที่กำหนดสำหรับเมาส์อยู่เหนือ อ่าน [IHyperlink](../ihyperlink/) |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | รับตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | กำหนดว่ารูปร่างอยู่ในกลุ่มหรือไม่ อ่านอย่างเดียว **bool** |
| **bool** [get_IsObjectIcon](./get_isobjecticon/)() override | กำหนดว่าวัตถุแสดงเป็นไอคอนหรือไม่ อ่าน **bool** |
| **bool** [get_IsObjectLink](./get_isobjectlink/)() override | กำหนดว่าวัตถุเชื่อมโยงกับไฟล์ภายนอกหรือไม่ อ่านอย่างเดียว **bool** |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | กำหนดว่ารูปร่างเป็น TextHolder_PPT หรือไม่ อ่านอย่างเดียว **bool** |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | คืนค่าอ็อบเจ็กต์ [LineFormat](../lineformat/) ที่บรรจุคุณสมบัติการจัดรูปแบบเส้นสำหรับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติเส้น อ่านอย่างเดียว [ILineFormat](../ilineformat/) |
| [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() override | คืนค่าพาธเต็มของไฟล์ที่เชื่อมโยง ชื่อไฟล์สั้นจะถูกใช้ อ่านอย่างเดียว [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | คืนค่าพาธเต็มของไฟล์ที่เชื่อมโยง ชื่อไฟล์ยาวจะถูกใช้ อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() override | คืนค่าพาธสัมพัทธ์ของไฟล์ที่เชื่อมโยงหากมี มิฉะนั้นคืนสตริงว่าง อ่านอย่างเดียว [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | คืนชื่อของรูปร่าง ต้องไม่เป็น null ใช้ค่าว่างหากต้องการ อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() override | คืนชื่อของวัตถุ อ่าน [System::String](../../system/string/) |
| [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() override | คืน ProgID ของวัตถุ อ่านอย่างเดียว [System::String](../../system/string/) |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | คืนตัวระบุที่เป็นเอกลักษณ์เฉพาะสไลด์ซึ่งคงที่ตลอดอายุของรูปร่างและทำให้ PowerPoint หรือโค้ด interop สามารถอ้างอิงรูปร่างได้อย่างเชื่อถือจากทุกตำแหน่งในเอกสาร อ่านอย่างเดียว **uint32_t** ดูเพิ่มเติม [Shape::get_UniqueId](../shape/get_uniqueid/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | คืนอ็อบเจ็กต์พาเรนท์ [GroupShape](../groupshape/) หากรูปร่างอยู่ในกลุ่ม มิฉะนั้นคืนค่า null อ่านอย่างเดียว [IGroupShape](../igroupshape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | คืนตัวเติมสำหรับรูปร่าง คืนค่า null หากรูปร่างไม่มีตัวเติม อ่านอย่างเดียว [IPlaceholder](../iplaceholder/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | คืนการนำเสนอแม่ของสไลด์ อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | คืนคุณสมบัติของเฟรมรูปร่างดิบ อ่าน [IShapeFrame](../ishapeframe/) |
| **float** [get_Rotation](../shape/get_rotation/)() override | คืนค่าจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน Z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา อ่าน **float** |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | คืนค่าการล็อคของรูปร่าง อ่านอย่างเดียว [IBaseShapeLock](../ibaseshapelock/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | คืนสไลด์พาเรนท์ของรูปร่าง อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() override | คืนอ็อบเจ็กต์คุณสมบัติการเติมภาพของ OleObject อ่านอย่างเดียว [IPictureFillFormat](../ipicturefillformat/) |
| [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() override | คืนชื่อเรื่องสำหรับไอคอน OleObject อ่าน [System::String](../../system/string/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | คืนอ็อบเจ็กต์ [ThreeDFormat](../threedformat/) ที่มีคุณสมบัติเอฟเฟกต์ 3D สำหรับรูปร่าง หมายเหตุ: อาจคืนค่า null สำหรับรูปร่างบางประเภทที่ไม่มีคุณสมบัติ 3D อ่านอย่างเดียว [IThreeDFormat](../ithreedformat/) |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | คืนตัวระบุภายในที่กำหนดตามการนำเสนอซึ่งใช้โดยแอดอินหรือโค้ดอื่น ๆ เนื่องจากค่าดังกล่าวอาจถูกกำหนดใหม่โดยผู้ใช้หรือโปรแกรม จึงไม่ควรถือว่าเป็นคีย์ที่เป็นเอกลักษณ์ถาวร อ่านอย่างเดียว **uint32_t** ดูเพิ่มเติม [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/) |
| **bool** [get_UpdateAutomatic](./get_updateautomatic/)() override | กำหนดว่าวัตถุฝังที่เชื่อมโยงถูกอัปเดตโดยอัตโนมัติเมื่อเปิดหรือพิมพ์การนำเสนอหรือไม่ อ่าน **bool** |
| **float** [get_Width](../shape/get_width/)() override | รับความกว้างของรูปร่าง หน่วยเป็นพอยท์ อ่าน **float** |
| **float** [get_X](../shape/get_x/)() override | รับพิกัด x ของมุมซ้ายบนของรูปร่าง หน่วยเป็นพอยท์ อ่าน **float** |
| **float** [get_Y](../shape/get_y/)() override | รับพิกัด y ของมุมซ้ายบนของรูปร่าง หน่วยเป็นพอยท์ อ่าน **float** |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | คืนตำแหน่งของรูปร่างในลำดับ z. Shapes[0] คืนรูปร่างที่อยู่ด้านหลังของลำดับ z, และ Shapes[Shapes.Count - 1] คืนรูปร่างที่อยู่ด้านหน้าของลำดับ z อ่านอย่างเดียว **int32_t** |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | คืนรูปร่างตัวเติมพื้นฐาน (รูปร่างจากเลย์เอาต์หรือสไลด์มาสเตอร์ที่รูปร่างปัจจัยสืบทอดมา) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชวัตถุกำหนดเองได้ |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | คืนรูปย่อของรูปร่าง [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) ชนิดขอบเขตรูปย่อของรูปร่างจะถูกใช้โดยค่าเริ่มต้น |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | คืนรูปย่อของรูปร่าง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | รับขอบเขตการแสดงผลของรูปร่างที่คำนวณจากเนื้อหาที่เรนเดอร์ |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่ targetType ระบุหรือไม่ คล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานของคำสั่ง lock() ของ C# เพื่อทำการล็อค เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทกำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างวัตถุ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการสร้างสำเนาสำหรับซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | กำหนดว่ารูปร่างนี้ไม่ใช่ตัวเติม |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | ตั้งข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง เขียน [System::String](../../system/string/) |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | ตั้งชื่อเรื่องของข้อความแทนที่ที่เชื่อมโยงกับรูปร่าง เขียน [System::String](../../system/string/) |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | คุณสมบัติกำหนดว่ารูปร่างจะแสดงผลในโหมดสีขาว-ดำอย่างไร เขียน [Slides::BlackWhiteMode](../blackwhitemode/) |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของเฟรมรูปร่าง เขียน [IShapeFrame](../ishapeframe/) |
| void [set_Height](../shape/set_height/)(**float**) override | ตั้งค่าความสูงของรูปร่าง หน่วยเป็นพอยท์ เขียน **float** |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | ตั้งค่าสถานะการซ่อนของรูปร่าง เขียน **bool** |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าการเชื่อมโยงที่กำหนดสำหรับคลิกเมาส์ เขียน [IHyperlink](../ihyperlink/) |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | ตั้งค่าการเชื่อมโยงที่กำหนดสำหรับเมาส์อยู่เหนือ เขียน [IHyperlink](../ihyperlink/) |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | ตั้งค่าตัวเลือก 'Mark as decorative' อ่าน/เขียน **bool** |
| void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) override | กำหนดว่าวัตถุแสดงเป็นไอคอนหรือไม่ เขียน **bool** |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | ตั้งค่าพาธเต็มของไฟล์ที่เชื่อมโยง ชื่อไฟล์ยาวจะถูกใช้ เขียน [System::String](../../system/string/) |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | ตั้งชื่อของรูปร่าง ต้องไม่เป็น null ใช้ค่าว่างหากต้องการ เขียน [System::String](../../system/string/) |
| void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) override | ตั้งชื่อของวัตถุ เขียน [System::String](../../system/string/) |
| void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) override | คืน ProgID ของวัตถุ อ่านอย่างเดียว [System::String](../../system/string/) |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | ตั้งค่าคุณสมบัติของเฟรมรูปร่างดิบ เขียน [IShapeFrame](../ishapeframe/) |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | ตั้งค่าจำนวนองศาที่รูปร่างที่ระบุถูกหมุนรอบแกน Z ค่าเป็นบวกแสดงการหมุนตามเข็มนาฬิกา ค่าเป็นลบแสดงการหมุนทวนเข็มนาฬิกา เขียน **float** |
| void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) override | ตั้งชื่อเรื่องสำหรับไอคอน OleObject เขียน [System::String](../../system/string/) |
| void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) override | กำหนดว่าวัตถุฝังที่เชื่อมโยงอัปเดตโดยอัตโนมัติเมื่อเปิดหรือพิมพ์การนำเสนอหรือไม่ เขียน **bool** |
| void [set_Width](../shape/set_width/)(**float**) override | ตั้งค่าความกว้างของรูปร่าง หน่วยเป็นพอยท์ เขียน **float** |
| void [set_X](../shape/set_x/)(**float**) override | ตั้งค่าพิกัด x ของมุมซ้ายบนของรูปร่าง หน่วยเป็นพอยท์ เขียน **float** |
| void [set_Y](../shape/set_y/)(**float**) override | ตั้งค่าพิกัด y ของมุมซ้ายบนของรูปร่าง หน่วยเป็นพอยท์ เขียน **float** |
| void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | ตั้งค่าข้อมูลเกี่ยวกับ OLE ที่ฝังอยู่ |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared) ให้สามารถสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงวัตถุกำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานของโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานของคำสั่ง lock() ของ C# เพื่อปลดล็อค เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ใช้ smart pointer หรือ ThisProtector แทน |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | บันทึกเนื้อหาของ [Shape](../shape/) เป็นไฟล์ SVG |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## หมายเหตุ


ตัวอย่างต่อไปนี้แสดงวิธีการเข้าถึงเฟรมวัตถุ OLE.

```cpp
// โหลดไฟล์ PPTX ไปยังอ็อบเจ็กต์การนำเสนอ
auto pres = System::MakeObject<Presentation>(u"AccessingOLEObjectFrame.pptx");

// เข้าถึงสไลด์แรก
auto slide = pres->get_Slides()->idx_get(0);
// แคสรูปทรงเป็น OleObjectFrame
System::SharedPtr<OleObjectFrame> oleObjectFrame = System::AsCast<OleObjectFrame>(slide->get_Shapes()->idx_get(0));
// อ่านวัตถุ OLE และเขียนลงดิสก์
if (oleObjectFrame != nullptr)
{
    // ดึงข้อมูลไฟล์ที่ฝังไว้
    System::ArrayPtr<uint8_t> data = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileData();
    // ดึงส่วนขยายของไฟล์ที่ฝังไว้
    System::String fileExtention = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileExtension();
    // สร้างเส้นทางเพื่อบันทึกไฟล์ที่แยกออก
    System::String extractedPath = System::String(u"excelFromOLE_out") + fileExtention;
    // บันทึกข้อมูลที่แยกออก
    auto stream = System::MakeObject<System::IO::FileStream>(extractedPath,
                                                             System::IO::FileMode::Create,
                                                             System::IO::FileAccess::Write);
    stream->Write(data, 0, data->get_Length());
}
```

## ดูเพิ่มเติม

* คลาส [GraphicalObject](../graphicalobject/)
* คลาส [IOleObjectFrame](../ioleobjectframe/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)