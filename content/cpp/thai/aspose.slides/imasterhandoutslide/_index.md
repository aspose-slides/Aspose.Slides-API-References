---
title: IMasterHandoutSlide
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แทนสไลด์หลักสำหรับเอกสารแจกจ่าย.
type: docs
weight: 2835
url: /th/aspose.slides/imasterhandoutslide/
---
## คลาส IMasterHandoutSlide

แทนสไลด์หลักสำหรับเอกสารแจกจ่าย.

```cpp
class IMasterHandoutSlide : public virtual Aspose::Slides::IBaseSlide,
                            public Aspose::Slides::Theme::IMasterThemeable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | ส่งคืนธีมที่มีประสิทธิภาพสำหรับวัตถุที่กำหนดธีมนี้. |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | กำหนดว่าตัวอย่าง [IBaseSlide](../ibaseslide/) สองรายการเท่ากันหรือไม่ ค่าที่ส่งกลับจะคำนวณตามโครงสร้างของสไลด์และเนื้อหาคงที่ สไลด์สองสไลด์เท่ากันถ้ารูปแบบ, สไตล์, ข้อความ, การเคลื่อนไหวและการตั้งค่าอื่น ๆ เป็นต้น เท่ากัน การเปรียบเทียบจะไม่คำนึงถึงค่าตัวระบุที่เป็นเอกลักษณ์ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าเวลาปัจจุบันใน Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ตรรกะของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยของ C#-style ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยของ C#-style ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | ค้นหาการปรากฏครั้งแรกของรูปทรงที่มีข้อความแทนที่ระบุ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | ส่งคืนพื้นหลังของสไลด์ อ่านอย่างเดียว [IBackground](../ibackground/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | ส่งคืนคอนโทรล ActiveX ที่ตำแหน่งที่ระบุ. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | ส่งคืนคอลlection ของคอนโทรล ActiveX บนสไลด์ อ่านอย่างเดียว [IControlCollection](../icontrolcollection/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | ส่งคืนข้อมูลแบบกำหนดเองของสไลด์ อ่านอย่างเดียว [ICustomData](../icustomdata/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() | ส่งคืนคอลlection ของแนวทางการวาดสำหรับสไลด์เอกสารแจกจ่ายหลัก อ่านอย่างเดียว [IDrawingGuidesCollection](../idrawingguidescollection/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterHandoutSlideHeaderFooterManager](../imasterhandoutslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | ส่งคืนผู้จัดการ HeaderFooter ของสไลด์เอกสารแจกจ่ายหลัก อ่านอย่างเดียว [IMasterHandoutSlideHeaderFooterManager](../imasterhandoutslideheaderfootermanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | ให้การเข้าถึงลิงก์ที่อยู่ในสไลด์อย่างง่าย อ่านอย่างเดียว [IHyperlinkQueries](../ihyperlinkqueries/). |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | ส่งคืนชื่อของสไลด์ อ่าน [System::String](../../system/string/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | ส่งคืนงานนำเสนอ อ่านอย่างเดียว [IPresentation](../ipresentation/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | ส่งคืนรูปทรงที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | ส่งคืนรูปทรงของสไลด์ อ่านอย่างเดียว [IShapeCollection](../ishapecollection/). |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | ระบุว่ารูปทรงบนสไลด์หลักควรแสดงบนสไลด์หรือไม่ สำหรับสไลด์หลักคุณสมบัตินี้จะส่งคืน **false** เสมอ อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | ส่งคืนสไลด์ฐาน อ่านอย่างเดียว [IBaseSlide](../ibaseslide/). |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | ส่งคืนรหัสของสไลด์ อ่านอย่างเดียว **uint32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | ส่งคืนอ็อบเจ็กต์ TransitionEx ที่มีข้อมูลเกี่ยวกับวิธีการเปลี่ยนสไลด์ที่ระบุระหว่างการนำเสนอ อ่านอย่างเดียว [ISlideShowTransition](../islideshowtransition/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/)\> [get_ThemeManager](../../aspose.slides.theme/imasterthemeable/get_thememanager/)() | ส่งคืนตัวจัดการธีมหลัก อ่านอย่างเดียว [IMasterThemeManager](../../aspose.slides.theme/imasterthememanager/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | ส่งคืนอ็อบเจ็กต์ไทม์ไลน์การเคลื่อนไหว อ่านอย่างเดียว [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นรูปแบบคล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถทำแฮชอ็อบเจ็กต์แบบกำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นรูปแบบคล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นรูปแบบคล้ายตัวดำเนินการ 'is' ของ C#. |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | รวมรันที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าในรูปทรงที่ยอมรับได้ทั้งหมด. |
| void [Lock](../../system/object/lock/)() | ใช้งานการล็อกของคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นรูปแบบคล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถคล cloning ชนิดที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์กำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | ตั้งชื่อสไลด์ เขียน [System::String](../../system/string/). |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | ระบุว่ารูปทรงบนสไลด์หลักควรแสดงบนสไลด์หรือไม่ สำหรับสไลด์หลักคุณสมบัตินี้จะส่งคืน **false** เสมอ เขียน **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared) เพื่อให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และส่งค่ากลับ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นรูปแบบคล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ใช้งานโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ใช้งานการปลดล็อกของคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IBaseSlide](../ibaseslide/)
* คลาส [IMasterThemeable](../../aspose.slides.theme/imasterthemeable/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)