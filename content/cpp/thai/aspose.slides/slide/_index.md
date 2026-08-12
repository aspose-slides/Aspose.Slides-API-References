---
title: Slide
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงสไลด์ในงานนำเสนอ.
type: docs
weight: 5175
url: /th/aspose.slides/slide/
---
## คลาส Slide

Represents a slide in a presentation.

```cpp
class Slide : public Aspose::Slides::BaseSlide,
              public Aspose::Slides::ISlide
```

## เมธอด

| Method | Description |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../baseslide/createthemeeffective/)() override | ส่งคืนธีมที่ใช้งานได้สำหรับสไลด์นี้. |
| **bool** [Equals](../baseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | กำหนดว่าตัวอย่าง [IBaseSlide](../ibaseslide/) สองอันเท่ากันหรือไม่ ค่าที่ส่งคืนคำนวนจากโครงสร้างของสไลด์และเนื้อหาคงที่ สไลด์สองสไลด์เท่ากันหากรูปทรง, สไตล์, ข้อความ, แอนิเมชัน และการตั้งค่าอื่น ๆ เป็นต้น เท่ากัน การเปรียบเทียบไม่ได้พิจารณาค่าตัวระบุที่เป็นเอกลักษณ์ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าของวันที่ปัจจุบันใน Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C#-style ที่ NaN สองค่าได้รับการพิจารณาเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C#-style ที่ NaN สองค่าได้รับการพิจารณาเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../baseslide/findshapebyalttext/)([System::String](../../system/string/)) override | ค้นหาการพบครั้งแรกของรูปร่างที่มีข้อความแทนที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../baseslide/get_background/)() override | ส่งคืนพื้นหลังของสไลด์ อ่านอย่างเดียว [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../baseslide/get_control/)(**int32_t**) override | ส่งคืนคอนโทรล ActiveX ที่ตำแหน่งกำหนด. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../baseslide/get_controls/)() override | ส่งคืนคอลเลกชันของคอนโทรล ActiveX บนสไลด์ อ่านอย่างเดียว [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../baseslide/get_customdata/)() override | ส่งคืนข้อมูลแบบกำหนดของสไลด์ อ่านอย่างเดียว [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideHeaderFooterManager](../islideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | ส่งคืนตัวจัดการ HeaderFooter ของสไลด์ อ่านอย่างเดียว [ISlideHeaderFooterManager](../islideheaderfootermanager/). |
| **bool** [get_Hidden](./get_hidden/)() override | กำหนดว่าสไลด์ที่ระบุถูกซ่อนในระหว่างการพรีเซนเทชันหรือไม่ อ่าน **bool**. |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../baseslide/get_hyperlinkqueries/)() override | ให้การเข้าถึงลิงก์ที่อยู่ภายในได้อย่างง่ายดาย อ่านอย่างเดียว [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)() override | ส่งคืนเลย์เอาต์สไลด์สำหรับสไลด์ปัจจุบัน อ่าน [ILayoutSlide](../ilayoutslide/). |
| [System::String](../../system/string/) [get_Name](../baseslide/get_name/)() override | ส่งคืนชื่อของสไลด์ อ่าน [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSlideManager](../inotesslidemanager/)\> [get_NotesSlideManager](./get_notesslidemanager/)() override | อนุญาตให้เข้าถึงสไลด์โน้ต, เพิ่มและลบได้ อ่านอย่างเดียว [INotesSlideManager](../inotesslidemanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../baseslide/get_presentation/)() override | ส่งคืนอินเทอร์เฟซ [IPresentation](../ipresentation/) อ่านอย่างเดียว [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../baseslide/get_shape/)(**int32_t**) override | ส่งคืนรูปร่างที่ตำแหน่งกำหนด อ่านอย่างเดียว [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../baseslide/get_shapes/)() override | ส่งคืนรูปร่างของสไลด์ อ่านอย่างเดียว [IShapeCollection](../ishapecollection/). |
| **bool** [get_ShowMasterShapes](./get_showmastershapes/)() override | กำหนดว่ารูปร่างบนมาสเตอร์สไลด์ควรแสดงบนสไลด์หรือไม่ อ่าน **bool**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | ส่งคืนสไลด์ฐาน อ่านอย่างเดียว [IBaseSlide](../ibaseslide/). |
| **uint32_t** [get_SlideId](../baseslide/get_slideid/)() override | ส่งคืน ID ของสไลด์ อ่านอย่างเดียว **uint32_t**. |
| **int32_t** [get_SlideNumber](./get_slidenumber/)() override | ส่งคืนจำนวนของสไลด์ ดัชนีของสไลด์ในคอลเลกชัน [Presentation::get_Slides()](../presentation/get_slides/) จะเท่ากับ SlideNumber - Presentation::get(set)_FirstSlideNumber เสมอ อ่าน **int32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../baseslide/get_slideshowtransition/)() override | ส่งคืนอ็อบเจ็กต์ Transition ที่มีข้อมูลเกี่ยวกับวิธีการที่สไลด์ที่ระบุก้าวต่อไปในการพรีเซนเทชัน อ่านอย่างเดียว [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](./get_thememanager/)() override | ส่งคืนผู้จัดการธีมที่แทนที่ อ่านอย่างเดียว [Theme::IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../baseslide/get_timeline/)() override | ส่งคืนอ็อบเจ็กต์ไทม์ไลน์แอนิเมชัน อ่านอย่างเดียว [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจ็กต์แบบกำหนดเอง. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)(**float**, **float**) override | ส่งคืนอ็อบเจ็กต์ Thumbnail Image ด้วยการสเกลแบบกำหนดเอง. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)() override | ส่งคืนอ็อบเจ็กต์ Thumbnail Image (20% ของขนาดจริง). |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::Drawing::Size](../../system.drawing/size/)) override | ส่งคืนอ็อบเจ็กต์ Thumbnail Image ด้วยขนาดที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>) override | ส่งคืนอ็อบเจ็กต์รูปภาพ tiff Thumbnail ด้วยพารามิเตอร์ที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) override | ส่งคืนอ็อบเจ็กต์ Thumbnail Image. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) override | ส่งคืนอ็อบเจ็กต์ Thumbnail Image ด้วยการสเกลแบบกำหนดเอง. |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](./getimage/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) override | ส่งคืนอ็อบเจ็กต์ Thumbnail Image ด้วยขนาดที่ระบุ. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IComment](../icomment/)\>\> [GetSlideComments](./getslidecomments/)([System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\>) override | ส่งคืนความคิดเห็นทั้งหมดของสไลด์ที่เพิ่มโดยผู้เขียนเฉพาะ. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เทียบเคียงกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เทียบเคียงกับออพเจอเรเตอร์ 'is' ของ C#. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | รวมรันที่มีรูปแบบเดียวกันในทุกย่อหน้าในรูปร่างที่รับได้ทั้งหมด. |
| virtual void [JoinPortionsWithSameFormatting](../baseslide/joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | รวมรันที่มีรูปแบบเดียวกันในทุกย่อหน้าในรูปร่างที่รับได้ทั้งหมด. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถทำสำเนาประเภทที่กำหนดเองได้. |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรกเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไร เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| void [Remove](./remove/)() override | ลบสไลด์ออกจากพรีเซนเทชัน. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงร่วมโดยค่าที่ระบุ. |
| void [Reset](./reset/)() override | รีเซ็ตตำแหน่ง, ขนาด และรูปแบบของทุกรูปร่างที่มีต้นแบบบน [LayoutSlide](../layoutslide/). |
| void [set_Hidden](./set_hidden/)(**bool**) override | กำหนดว่าสไลด์ที่ระบุถูกซ่อนในระหว่างการพรีเซนเทชันหรือไม่ เขียน **bool**. |
| void [set_LayoutSlide](./set_layoutslide/)([System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\>) override | ตั้งค่าเลย์เอาต์สไลด์สำหรับสไลด์ปัจจุบัน เขียน [ILayoutSlide](../ilayoutslide/). |
| void [set_Name](../baseslide/set_name/)([System::String](../../system/string/)) override | ตั้งชื่อตัวสไลด์ เขียน [System::String](../../system/string/). |
| void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) override | กำหนดว่ารูปร่างบนมาสเตอร์สไลด์ควรแสดงบนสไลด์หรือไม่ เขียน **bool**. |
| void [set_SlideNumber](./set_slidenumber/)(**int32_t**) override | ส่งคืนจำนวนของสไลด์ ดัชนีของสไลด์ในคอลเลกชัน [Presentation::get_Slides()](../presentation/get_slides/) จะเท่ากับ SlideNumber - Presentation::get(set)_FirstSlideNumber เสมอ เขียน **int32_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทนที่ shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WriteAsEmf](./writeasemf/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหาสไลด์เป็นไฟล์ EMF. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG. |
| void [WriteAsSvg](./writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | บันทึกเนื้อหาสไลด์เป็นไฟล์ SVG. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* Class [BaseSlide](../baseslide/)
* Class [ISlide](../islide/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)