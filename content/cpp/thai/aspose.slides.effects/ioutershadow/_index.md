---
title: IOuterShadow
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงถึงเอฟเฟกต์เงานอก.
type: docs
weight: 885
url: /th/aspose.slides.effects/ioutershadow/
---
## IOuterShadow คลาส


Represents an Outer Shadow effect.

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าทุกค่า รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# โดยที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าทุกค่า รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) รัศมี, หน่วยเป็นจุด. ค่าเริ่มต้น – 0 pt. อ่าน **double**. |
| virtual **float** [get_Direction](./get_direction/)() | ทิศทางของเงา, หน่วยเป็นองศา. ค่าเริ่มต้น – 0 ° (จากซ้ายไปขวา). อ่าน **float**. |
| virtual **double** [get_Distance](./get_distance/)() | ระยะห่างของเงาจากวัตถุ, หน่วยเป็นจุด. ค่าเริ่มต้น – 0 pt. อ่าน **double**. |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | การจัดเรียงสี่เหลี่ยม. ค่าเริ่มต้น – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). อ่าน [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | บ่งชี้ว่าเงาจะหมุนพร้อมกับรูปร่างหรือไม่. ค่าเริ่มต้น – true. อ่าน **bool**. |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | อัตราส่วนการสเกลแนวนอน, หน่วยเป็นเปอร์เซ็นต์ของขนาดเดิม. การสเกลลบทำให้พลิก. ค่าเริ่มต้น – 100 %. อ่าน **double**. |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | อัตราส่วนการสเกลแนวตั้ง, หน่วยเป็นเปอร์เซ็นต์ของขนาดเดิม. การสเกลลบทำให้พลิก. ค่าเริ่มต้น – 100 %. อ่าน **double**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | สีของเงา. ค่าเริ่มต้น – สีดำอัตโนมัติ (ขึ้นกับธีม). อ่านอย่างเดียว [IColorFormat](../../aspose.slides/icolorformat/). |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | มุมเอียงแนวนอน, หน่วยเป็นองศา. ค่าเริ่มต้น – 0 °. อ่าน **double**. |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | มุมเอียงแนวตั้ง, หน่วยเป็นองศา. ค่าเริ่มต้น – 0 °. อ่าน **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่สัมพันธ์กับอ็อบเจ็กต์. |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | รับข้อมูลที่มีประสิทธิภาพโดยมีการสืบทอดใช้. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เหมือนกับเมธอด [Object.GetHashCode()](../../system/object/gethashcode/) ของ C#. เปิดใช้งานการทำแฮชของอ็อบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เหมือนกับการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เหมือนกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เหมือนกับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C#. เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์ตามอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์ตามอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดตัวนับอ้างอิงร่วมลงตามค่าที่ระบุ. |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) รัศมี, หน่วยเป็นจุด. ค่าเริ่มต้น – 0 pt. เขียน **double**. |
| virtual void [set_Direction](./set_direction/)(**float**) | ทิศทางของเงา, หน่วยเป็นองศา. ค่าเริ่มต้น – 0 ° (จากซ้ายไปขวา). เขียน **float**. |
| virtual void [set_Distance](./set_distance/)(**double**) | ระยะห่างของเงาจากวัตถุ, หน่วยเป็นจุด. ค่าเริ่มต้น – 0 pt. เขียน **double**. |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | การจัดเรียงสี่เหลี่ยม. ค่าเริ่มต้น – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). เขียน [RectangleAlignment](../../aspose.slides/rectanglealignment/). |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | บ่งชี้ว่าเงาจะหมุนพร้อมกับรูปร่างหรือไม่. ค่าเริ่มต้น – true. เขียน **bool**. |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | อัตราส่วนการสเกลแนวนอน, หน่วยเป็นเปอร์เซ็นต์ของขนาดเดิม. การสเกลลบทำให้พลิก. ค่าเริ่มต้น – 100 %. เขียน **double**. |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | อัตราส่วนการสเกลแนวตั้ง, หน่วยเป็นเปอร์เซ็นต์ของขนาดเดิม. การสเกลลบทำให้พลิก. ค่าเริ่มต้น – 100 %. เขียน **double**. |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | มุมเอียงแนวนอน, หน่วยเป็นองศา. ค่าเริ่มต้น – 0 °. เขียน **double**. |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | มุมเอียงแนวตั้ง, หน่วยเป็นองศา. ค่าเริ่มต้น – 0 °. เขียน **double**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | กำหนดเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เหมือนกับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C#. เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IImageTransformOperation](../iimagetransformoperation/)
* คลาส [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* เนมสเปซ [Aspose::Slides::Effects](../)
* ไลบรารี [Aspose.Slides](../../)