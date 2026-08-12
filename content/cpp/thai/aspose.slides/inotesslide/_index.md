---
title: INotesSlide
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เป็นตัวแทนของสไลด์โน้ตในงานนำเสนอ
type: docs
weight: 3017
url: /th/aspose.slides/inotesslide/
---
## INotesSlide คลาส

แสดงสไลด์โน้ตในงานนำเสนอ.

```cpp
class INotesSlide : public virtual Aspose::Slides::IBaseSlide,
                    public Aspose::Slides::Theme::IOverrideThemeable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | ส่งคืนธีมที่มีผลสำหรับวัตถุที่สามารถกำหนดธีมได้ |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | กำหนดว่าตัวอย่าง [IBaseSlide](../ibaseslide/) สองอันเท่ากันหรือไม่ ค่าที่ส่งกลับจะคำนวณจากโครงสร้างของสไลด์และเนื้อหาคงที่ สไลด์สองสไลด์จะเท่ากันถ้า shape, style, text, animation และการตั้งค่าอื่น ๆ เป็นต้นเท่ากัน การเปรียบเทียบจะไม่พิจารณาค่าตัวระบุที่ไม่ซ้ำกัน เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าที่เป็นวันที่ปัจจุบันใน Date [Placeholder](../placeholder/) |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยตามสไตล์ของ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยตามสไตล์ของ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อวัตถุประสงค์ภายในเท่านั้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | ค้นหา shape ที่มีข้อความแทนที่ระบุเป็นการปรากฏครั้งแรก |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | ส่งคืนพื้นหลังของสไลด์ อ่านได้อย่างเดียว [IBackground](../ibackground/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | ส่งคืนควบคุม ActiveX ที่ตำแหน่งที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | ส่งคืนคอลเลกชันของควบคุม ActiveX บนสไลด์ อ่านได้อย่างเดียว [IControlCollection](../icontrolcollection/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | ส่งคืนข้อมูลแบบกำหนดเองของสไลด์ อ่านได้อย่างเดียว [ICustomData](../icustomdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INotesSlideHeaderFooterManager](../inotesslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | ส่งคืนผู้จัดการ HeaderFooter ของโน้ตสไลด์ อ่านได้อย่างเดียว [INotesSlideHeaderFooterManager](../inotesslideheaderfootermanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | ให้การเข้าถึงไฮเปอร์ลิงก์ที่บรรจุอยู่ได้อย่างง่าย อ่านได้อย่างเดียว [IHyperlinkQueries](../ihyperlinkqueries/) |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | ส่งคืนชื่อของสไลด์ อ่าน [System::String](../../system/string/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_NotesTextFrame](./get_notestextframe/)() | ส่งคืน [TextFrame](../textframe/) ที่มีข้อความโน้ต หากมีอยู่ อ่านได้อย่างเดียว [ITextFrame](../itextframe/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_ParentSlide](./get_parentslide/)() | ส่งคืน ParentSlide อ่านได้อย่างเดียว [ISlide](../islide/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | ส่งคืนการนำเสนอ อ่านได้อย่างเดียว [IPresentation](../ipresentation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | ส่งคืน shape ที่ตำแหน่งที่ระบุ อ่านได้อย่างเดียว [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | ส่งคืน shape ของสไลด์ อ่านได้อย่างเดียว [IShapeCollection](../ishapecollection/) |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | ระบุว่าควรแสดง shape บนสไลด์มาสเตอร์บนสไลด์หรือไม่ สำหรับสไลด์มาสเตอร์เอง property นี้จะคืนค่า **false** เสมอ อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | ส่งคืนสไลด์ฐาน อ่านได้อย่างเดียว [IBaseSlide](../ibaseslide/) |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | ส่งคืน ID ของสไลด์ อ่านได้อย่างเดียว **uint32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | ส่งคืนอ็อบเจกต์ TransitionEx ที่บรรจุข้อมูลว่าการเปลี่ยนสไลด์ที่ระบุดำเนินการอย่างไรในช่วงการแสดงสไลด์ อ่านได้อย่างเดียว [ISlideShowTransition](../islideshowtransition/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | ส่งคืนผู้จัดการธีมที่แทนที่ อ่านได้อย่างเดียว [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | ส่งคืนอ็อบเจกต์ไทม์ไลน์แอนิเมชัน อ่านได้อย่างเดียว [IAnimationTimeLine](../ianimationtimeline/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแบบจำลองของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชวัตถุกำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ เป็นแบบจำลองของการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นแบบจำลองของออปเรเตอร์ 'is' ของ C# |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | รวม run ที่มีการจัดรูปแบบเดียวกันในทุกย่อหน้าในทุก shape ที่ยอมรับ |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่เหมือนคำสั่ง lock() ของ C# การเรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบจำลองของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทกำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างวัตถุ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอ้อะไรเลย เพียงแค่เริ่มต้นวัตถุใหม่และเปิดให้ซับคลาสสร้างสำเนา |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ออเปอร์เรเตอร์มอบหมาย ไม่ได้คัดลอ้อะไรเลย เพียงแค่เริ่มต้นวัตถุใหม่และเปิดให้ซับคลาสสร้างสำเนา |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | ทำการอ้างอิงเปรียบเทียบวัตถุประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | ตั้งชื่อสไลด์ เขียน [System::String](../../system/string/) |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | ระบุว่าควรแสดง shape บนสไลด์มาสเตอร์บนสไลด์หรือไม่ สำหรับสไลด์มาสเตอร์เอง property นี้จะคืนค่า **false** เสมอ เขียน **bool** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตลำดับที่ n เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแบบจำลองของเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงวัตถุกำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เช่น typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อคของคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IBaseSlide](../ibaseslide/)
* คลาส [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)