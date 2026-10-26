---
title: ILayoutSlide
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: แสดงถึงสไลด์เลเอาต์.
type: docs
weight: 2640
url: /th/aspose.slides/ilayoutslide/
---
## ILayoutSlide คลาส

แสดงถึงสไลด์เลเอาต์

```cpp
class ILayoutSlide : public virtual Aspose::Slides::IBaseSlide,
                     public Aspose::Slides::Theme::IOverrideThemeable
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThemeEffectiveData](../../aspose.slides.theme/ithemeeffectivedata/)\> [CreateThemeEffective](../../aspose.slides.theme/ithemeable/createthemeeffective/)() | คืนค่าเทมเพลตที่ใช้งานได้สำหรับวัตถุที่รองรับธีมนี้ |
| virtual **bool** [Equals](../ibaseslide/equals/)([System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\>) | กำหนดว่าตัวอย่างสอง [IBaseSlide](../ibaseslide/) เท่ากันหรือไม่ ค่าที่คืนมาถูกคำนวณตามโครงสร้างของสไลด์และเนื้อหาคงที่ สไลด์สองสไลด์เท่ากันหากรูปทรง, สไตล์, ข้อความ, การเคลื่อนไหวและการตั้งค่าอื่นๆ เป็นต้นเท่ากัน การเปรียบเทียบไม่พิจารณาค่าตัวระบุที่ไม่ซ้ำกัน เช่น SlideId และเนื้อหาแบบไดนามิก เช่นค่าปัจจุบันของวันที่ใน Date [Placeholder](../placeholder/) |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [FindShapeByAltText](../ibaseslide/findshapebyalttext/)([System::String](../../system/string/)) | ค้นหาการปรากฏครั้งแรกของรูปร่างที่มีข้อความแทนที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBackground](../ibackground/)\> [get_Background](../ibaseslide/get_background/)() | คืนค่าส่วนพื้นหลังของสไลด์ อ่านอย่างเดียว [IBackground](../ibackground/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControl](../icontrol/)\> [get_Control](../ibaseslide/get_control/)(**int32_t**) | คืนค่า ActiveX control ที่ตำแหน่งที่ระบุ |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IControlCollection](../icontrolcollection/)\> [get_Controls](../ibaseslide/get_controls/)() | คืนค่าคอลเลกชันของ ActiveX controls บนสไลด์ อ่านอย่างเดียว [IControlCollection](../icontrolcollection/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ibaseslide/get_customdata/)() | คืนค่าข้อมูลกำหนดเองของสไลด์ อ่านอย่างเดียว [ICustomData](../icustomdata/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDrawingGuidesCollection](../idrawingguidescollection/)\> [get_DrawingGuides](./get_drawingguides/)() | คืนค่าคอลเลกชันของแนวทางการวาดสำหรับสไลด์เลเอาต์ อ่านอย่างเดียว [IDrawingGuidesCollection](../idrawingguidescollection/) |
| virtual **bool** [get_HasDependingSlides](./get_hasdependingslides/)() | คืนค่า true หากมีสไลด์อย่างน้อยหนึ่งสไลด์ที่ขึ้นอยู่กับสไลด์เลเอาต์นี้ อ่านอย่างเดียว **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlideHeaderFooterManager](../ilayoutslideheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | คืนค่า HeaderFooter manager ของสไลด์เลเอาต์ อ่านอย่างเดียว [ILayoutSlideHeaderFooterManager](../ilayoutslideheaderfootermanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](../ibaseslide/get_hyperlinkqueries/)() | ให้การเข้าถึงลิงก์ที่ใส่อยู่ในสไลด์อย่างง่าย อ่านอย่างเดียว [IHyperlinkQueries](../ihyperlinkqueries/) |
| virtual [SlideLayoutType](../slidelayouttype/) [get_LayoutType](./get_layouttype/)() | คืนค่าชนิดของเลเอาต์ของสไลด์เลเอาต์นี้ อ่านอย่างเดียว [SlideLayoutType](../slidelayouttype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [get_MasterSlide](./get_masterslide/)() | คืนค่าสไลด์แม่สำหรับเลเอาต์ อ่าน [IMasterSlide](../imasterslide/) |
| virtual [System::String](../../system/string/) [get_Name](../ibaseslide/get_name/)() | คืนชื่อนของสไลด์ อ่าน [System::String](../../system/string/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILayoutPlaceholderManager](../ilayoutplaceholdermanager/)\> [get_PlaceholderManager](./get_placeholdermanager/)() | คืนค่า placeholder manager ของสไลด์เลเอาต์ อ่านอย่างเดียว [ILayoutPlaceholderManager](../ilayoutplaceholdermanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | คืนค่าการนำเสนอ อ่านอย่างเดียว [IPresentation](../ipresentation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](../ibaseslide/get_shape/)(**int32_t**) | คืนค่ารูปร่างที่ตำแหน่งที่ระบุ อ่านอย่างเดียว [Aspose::Slides::IShape](../ishape/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](../ibaseslide/get_shapes/)() | คืนรูปร่างของสไลด์ อ่านอย่างเดียว [IShapeCollection](../ishapecollection/) |
| virtual **bool** [get_ShowMasterShapes](../ibaseslide/get_showmastershapes/)() | ระบุว่ารูปร่างบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่ สำหรับสไลด์แม่เองคุณสมบัตินี้คืนค่า **false** เสมอ อ่าน **bool** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | คืนค่าสไลด์ฐาน อ่านอย่างเดียว [IBaseSlide](../ibaseslide/) |
| virtual **uint32_t** [get_SlideId](../ibaseslide/get_slideid/)() | คืนค่า ID ของสไลด์ อ่านอย่างเดียว **uint32_t** |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideShowTransition](../islideshowtransition/)\> [get_SlideShowTransition](../ibaseslide/get_slideshowtransition/)() | คืนค่าอ็อบเจ็กต์ TransitionEx ที่มีข้อมูลเกี่ยวกับการเปลี่ยนสไลด์ที่ระบุระหว่างการนำเสนอ อ่านอย่างเดียว [ISlideShowTransition](../islideshowtransition/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/)\> [get_ThemeManager](../../aspose.slides.theme/ioverridethemeable/get_thememanager/)() | คืนค่า override theme manager อ่านอย่างเดียว [IOverrideThemeManager](../../aspose.slides.theme/ioverridethememanager/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAnimationTimeLine](../ianimationtimeline/)\> [get_Timeline](../ibaseslide/get_timeline/)() | คืนค่าอ็อบเจ็กต์ animation timeline อ่านอย่างเดียว [IAnimationTimeLine](../ianimationtimeline/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับข้อมูลโครงสร้างตัวนับการอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\>\> [GetDependingSlides](./getdependingslides/)() | คืนค่าอาเรย์ที่มีสไลด์ทั้งหมดที่ขึ้นอยู่กับสไลด์เลเอาต์นี้ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแบบเดียวกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ช่วยให้ทำแฮชของอ็อบเจ็กต์กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์ เป็นแบบเดียวกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType เป็นแบบเดียวกับโอเปอเรเตอร์ 'is' ของ C# |
| virtual void [JoinPortionsWithSameFormatting](../ibaseslide/joinportionswithsameformatting/)() | รวมรันที่มีรูปแบบเดียวกันในย่อหน้าทั้งหมดของรูปร่างที่รับได้ทั้งหมด |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ตามคำสั่ง lock() ของ C# เพื่อทำการล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบเดียวกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ช่วยให้ทำการโคลนประเภทกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์ตามการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์ตามการอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงของอ็อบเจ็กต์ประเภทค่า กับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การแปรรูปเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การแปรรูปเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายค่า |
| virtual void [Remove](./remove/)() | ลบเลเอาต์ออกจากการนำเสนอ |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [set_MasterSlide](./set_masterslide/)([System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\>) | กำหนดสไลด์แม่สำหรับเลเอาต์ เขียน [IMasterSlide](../imasterslide/) |
| virtual void [set_Name](../ibaseslide/set_name/)([System::String](../../system/string/)) | กำหนดชื่อของสไลด์ เขียน [System::String](../../system/string/) |
| virtual void [set_ShowMasterShapes](../ibaseslide/set_showmastershapes/)(**bool**) | ระบุว่ารูปร่างบนสไลด์แม่ควรแสดงบนสไลด์หรือไม่ สำหรับสไลด์แม่เองคุณสมบัตินี้คืนค่า **false** เสมอ เขียน **bool** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์แม่แบบที่ n เป็น weak pointer (แทน shared) ทำให้สามารถสลับ pointer ใน container ไปเป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับการอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่าตัวนับการอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแบบเดียวกับเมธอด C# [Object.ToString()](../../system/object/tostring/) ช่วยให้แปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ตามโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ตามคำสั่ง lock() ของ C# เพื่อปลดล็อก เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference ควรไม่เรียกโดยตรง ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference ควรไม่เรียกโดยตรง ใช้ smart pointers หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IBaseSlide](../ibaseslide/)
* คลาส [IOverrideThemeable](../../aspose.slides.theme/ioverridethemeable/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)