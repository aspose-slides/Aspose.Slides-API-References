---
title: BaseSlide
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนข้อมูลทั่วไปสำหรับสไลด์ทุกประเภท
type: docs
weight: 170
url: /th/aspose.slides/baseslide/
---
## BaseSlide คลาส

Represents common data for all slide types.

```cpp
class BaseSlide : public virtual Aspose::Slides::IBaseSlide,
                  public Aspose::Slides::IDOMObject,
                  public Aspose::Slides::IStyleColorOwner
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](./createthemeeffective/)() override | Returns an effective theme for this slide. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) override | กำหนดว่าตัวอย่าง [IBaseSlide](../ibaseslide/) สองอันเท่ากันหรือไม่ ค่าที่ส่งกลับจะคำนวณตามโครงสร้างสไลด์และเนื้อหาคงที่ สไลด์สองสไลด์เท่ากันหากรูปทรง, สไตล์, ข้อความ, แอนิเมชันและการตั้งค่าอื่น ๆ ฯลฯ เท่ากัน การเปรียบเทียบจะไม่คำนึงถึงค่าตัวระบุที่เป็นเอกลักษณ์ เช่น SlideId และเนื้อหาแบบไดนามิก เช่น ค่าที่เป็นวันที่ปัจจุบันใน Date [Placeholder](../placeholder/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ตรรกะของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขลอยจุดในรูปแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขลอยจุดในรูปแบบ C# ซึ่ง NaN สองค่าถือว่าเท่ากัน แม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](./findshapebyalttext/)([System::String](../../system/string/)) override | ค้นหาการปรากฏครั้งแรกของรูปทรงที่มีข้อความแทนที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](./get_background/)() override | คืนค่าพื้นหลังของสไลด์ อ่านอย่างเดียว [IBackground](../ibackground/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](./get_control/)(**int32_t**) override | คืนค่า ActiveX คอนโทรลที่ดัชนีที่ระบุ. |
| [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](./get_controls/)() override | คืนค่าคอลเลกชันของ ActiveX คอนโทรลบนสไลด์ อ่านอย่างเดียว [IControlCollection](../icontrolcollection/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | คืนค่าข้อมูลกำหนดเองของสไลด์ อ่านอย่างเดียว [ICustomData](../icustomdata/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() override | ให้การเข้าถึงลิงก์ที่ฝังอยู่ได้อย่างง่ายดาย อ่านอย่างเดียว [IHyperlinkQueries](../ihyperlinkqueries/). |
| [System::String](../../system/string/) [get_Name](./get_name/)() override | คืนชื่อของสไลด์ อ่าน [System::String](../../system/string/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](./get_presentation/)() override | คืนส่วนติดต่อ [IPresentation](../ipresentation/) อ่านอย่างเดียว [IPresentation](../ipresentation/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)(**int32_t**) override | คืนรูปทรงที่ตำแหน่งดัชนีที่ระบุ อ่านอย่างเดียว [Aspose::Slides::IShape](../ishape/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](./get_shapes/)() override | คืนรูปทรงของสไลด์ อ่านอย่างเดียว [IShapeCollection](../ishapecollection/). |
| virtual **bool** [get_ShowMasterShapes](./get_showmastershapes/)() | ระบุว่ารูปทรงบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่ สำหรับสไลด์แม่เองคุณสมบัตินี้จะคืนค่า **false** เสมอ อ่าน **bool**. |
| **uint32_t** [get_SlideId](./get_slideid/)() override | คืนค่า ID ของสไลด์ อ่านอย่างเดียว **uint32_t**. |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](./get_slideshowtransition/)() override | คืนวัตถุ Transition ที่มีข้อมูลเกี่ยวกับวิธีการดำเนินสไลด์ที่ระบุระหว่างการแสดงสไลด์ อ่านอย่างเดียว [ISlideShowTransition](../islideshowtransition/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](./get_timeline/)() override | คืนวัตถุไทม์ไลน์ของแอนิเมชัน อ่านอย่างเดียว [IAnimationTimeLine](../ianimationtimeline/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). รองรับการแฮชของอ็อบเจกต์กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอนาล็อกของโอเปอเรเตอร์ 'is' ของ C#. |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | รวมรันที่มีรูปแบบเดียวกันในทุกย่อหน้าและรูปทรงที่ยอมรับทั้งหมด. |
| virtual void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\>) | รวมรันที่มีรูปแบบเดียวกันในทุกย่อหน้าและรูปทรงที่ยอมรับทั้งหมด. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). รองรับการโคลนประเภทกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดให้สร้างสำเนาของซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดให้สร้างสำเนาของซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจกต์ชนิดค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_Name](./set_name/)([System::String](../../system/string/)) override | ตั้งชื่อสไลด์. เขียน [System::String](../../system/string/). |
| virtual void [set_ShowMasterShapes](./set_showmastershapes/)(**bool**) | ระบุว่ารูปทรงบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่ สำหรับสไลด์แม่เองคุณสมบัตินี้จะคืนค่า **false** เสมอ เขียน **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เท็มเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). รองรับการแปลงอ็อบเจกต์กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IBaseSlide](../ibaseslide/)
* คลาส [IDOMObject](../idomobject/)
* คลาส [IStyleColorOwner](../istylecolorowner/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)