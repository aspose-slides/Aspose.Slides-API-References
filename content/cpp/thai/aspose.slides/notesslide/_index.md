---
title: NotesSlide
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: เป็นตัวแทนของสไลด์โน้ตในงานนำเสนอ.
type: docs
weight: 4564
url: /th/aspose.slides/notesslide/
---
## NotesSlide คลาส

เป็นตัวแทนของสไลด์โน้ตในงานนำเสนอ.

```cpp
class NotesSlide : public Aspose::Slides::BaseSlide,
                   public Aspose::Slides::INotesSlide
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../baseslide/createthemeeffective/)() override | คืนค่า theme ที่มีประสิทธิผลสำหรับสไลด์นี้. |
| **bool** [Equals](../baseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | กำหนดว่าตัวอย่าง [IBaseSlide](../ibaseslide/) สองตัวเท่ากันหรือไม่ ค่าที่คืนจะคำนวณจากโครงสร้างของสไลด์และเนื้อหาคงที่ สไลด์สองสไลด์เท่ากันถ้ารูปทรง, สไตล์, ข้อความ, แอนิเมชั่นและการตั้งค่าอื่น ๆ เป็นต้น เท่ากัน การเปรียบเทียบจะไม่คำนึงถึงค่า unique identifier เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าของวันที่ปัจจุบันใน Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ NaN ทั้งสองถือเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ NaN ทั้งสองถือเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับภายในเท่านั้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../baseslide/findshapebyalttext/)([System::String](../../system/string/)) override | ค้นหาการพบครั้งแรกของรูปทรงที่มีข้อความแทนที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../baseslide/get_background/)() override | คืนค่าพื้นหลังของสไลด์. อ่านอย่างเดียว [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../baseslide/get_control/)(**int32_t**) override | คืนค่า ActiveX control ที่ตำแหน่งที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../baseslide/get_controls/)() override | คืนค่าคอลเลกชันของ ActiveX controls บนสไลด์. อ่านอย่างเดียว [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../baseslide/get_customdata/)() override | คืนค่าข้อมูล custom ของสไลด์. อ่านอย่างเดียว [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSlideHeaderFooterManager](../inotesslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | คืนค่า HeaderFooter manager ของ notes slide. อ่านอย่างเดียว [INotesSlideHeaderFooterManager](../inotesslideheaderfootermanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../baseslide/get_hyperlinkqueries/)() override | ให้การเข้าถึงลิงก์ไฮเปอร์เท็กซ์ที่มีอยู่ได้ง่าย. อ่านอย่างเดียว [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::String](../../system/string/) [get_Name](../baseslide/get_name/)() override | คืนค่าชื่อของสไลด์. อ่าน [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../itextframe/)\> [get_NotesTextFrame](./get_notestextframe/)() override | คืนค่า [TextFrame](../textframe/) ที่มีข้อความของโน้ต หากมี. อ่านอย่างเดียว [ITextFrame](../itextframe/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_ParentSlide](./get_parentslide/)() override | คืนค่าสไลด์แม่. อ่านอย่างเดียว [ISlide](../islide/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../baseslide/get_presentation/)() override | คืนค่า interface [IPresentation](../ipresentation/). อ่านอย่างเดียว [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../baseslide/get_shape/)(**int32_t**) override | คืนค่ารูปทรงที่ตำแหน่งที่ระบุ. อ่านอย่างเดียว [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../baseslide/get_shapes/)() override | คืนค่ารูปทรงของสไลด์. อ่านอย่างเดียว [IShapeCollection](../ishapecollection/). |
| **bool** [get_ShowMasterShapes](./get_showmastershapes/)() override | กำหนดว่ารูปทรงบน master slide ควรแสดงบนสไลด์หรือไม่. อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | คืนค่า base slide. อ่านอย่างเดียว [IBaseSlide](../ibaseslide/). |
| **uint32_t** [get_SlideId](../baseslide/get_slideid/)() override | คืนค่า ID ของสไลด์. อ่านอย่างเดียว **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../baseslide/get_slideshowtransition/)() override | คืนค่าอ็อบเจ็กต์ Transition ที่มีข้อมูลเกี่ยวกับการเลื่อนสไลด์ที่ระบุในระหว่างการแสดงสไลด์. อ่านอย่างเดียว [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | คืนค่า overriding theme manager. อ่านอย่างเดียว [Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../baseslide/get_timeline/)() override | คืนค่าอ็อบเจ็กต์ animation timeline. อ่านอย่างเดียว [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นเทียบเคียงของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์ custom ได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นเทียบเคียงของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่. เป็นเทียบเคียงของออเปอเรเตอร์ 'is' ของ C#. |
| void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)() override | รวมรันที่มีรูปแบบเดียวกันในทุกย่อหน้าของรูปทรงที่ยอมรับทั้งหมด. |
| virtual void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | รวมรันที่มีรูปแบบเดียวกันในทุกย่อหน้าของรูปทรงที่ยอมรับทั้งหมด. |
| void [Lock](../../system/object/lock/)() | ทำตามคำสั่ง lock() ของ C# เพื่อล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นเทียบเคียงของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถคล cloning ชนิด custom ได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. ไม่ได้คัดลอกข้อมูลใด ๆ จริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกข้อมูลใด ๆ จริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาสำหรับคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_Name](../baseslide/set_name/)([System::String](../../system/string/)) override | ตั้งชื่อสไลด์. เขียน [System::String](../../system/string/). |
| void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) override | กำหนดว่ารูปทรงบน master slide ควรแสดงบนสไลด์หรือไม่. เขียน **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า template argument ที่ n เป็น weak pointer (แทนที่ shared). ทำให้สามารถสลับ pointers ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นเทียบเคียงของเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจ็กต์ custom เป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่คล้าย typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [BaseSlide](../baseslide/)
* คลาส [INotesSlide](../inotesslide/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)