---
title: OuterShadow
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนของเอฟเฟกต์เงานอก.
type: docs
weight: 1041
url: /th/aspose.slides.effects/outershadow/
---
## OuterShadow คลาส

เป็นตัวแทนของเอฟเฟกต์เงานอก.

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | กำหนดว่าค่า [OuterShadow](./) ที่ระบุเท่ากับ [OuterShadow](./) ปัจจุบันหรือไม่ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้ภายในเท่านั้น |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) รัศมี, หน่วยเป็น pt. ค่าเริ่มต้น – 0 pt. อ่าน **double** |
| **float** [get_Direction](./get_direction/)() override | ทิศทางของเงา, หน่วยเป็นองศา. ค่าเริ่มต้น – 0 \u00B0 (จากซ้ายไปขวา). อ่าน **float** |
| **double** [get_Distance](./get_distance/)() override | ระยะห่างของเงาจากอ็อบเจ็กต์, หน่วยเป็น pt. ค่าเริ่มต้น – 0 pt. อ่าน **double** |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | คืนค่าพาเรนต์ [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). อ่านอย่างเดียว [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | การจัดแนวสี่เหลี่ยม. ค่าเริ่มต้น – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). อ่าน [RectangleAlignment](../../aspose.slides/rectanglealignment/) |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | ระบุว่าเงาจะหมุนพร้อมกับรูปร่างหรือไม่. ค่าเริ่มต้น – true. อ่าน **bool** |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | แฟกเตอร์สเกลแนวนอน, เป็นเปอร์เซ็นต์ของขนาดเดิม. การสเกลแบบลบทำให้พลิก. ค่าเริ่มต้น – 100 %. อ่าน **double** |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | แฟกเตอร์สเกลแนวตั้ง, เป็นเปอร์เซ็นต์ของขนาดเดิม. การสเกลแบบลบทำให้พลิก. ค่าเริ่มต้น – 100 %. อ่าน **double** |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | สีของเงา. ค่าเริ่มต้น – สีดำอัตโนมัติ (ขึ้นอยู่กับธีม). อ่านอย่างเดียว [IColorFormat](../../aspose.slides/icolorformat/) |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | มุมเอียงแนวนอน, หน่วยเป็นองศา. ค่าเริ่มต้น – 0 \u00B0. อ่าน **double** |
| **double** [get_SkewVertical](./get_skewvertical/)() override | มุมเอียงแนวตั้ง, หน่วยเป็นองศา. ค่าเริ่มต้น – 0 \u00B0. อ่าน **double** |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | เวอร์ชัน. อ่านอย่างเดียว **uint32_t** |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | รับข้อมูลเอฟเฟกต์ Outer Shadow ที่มีผลโดยการสืบทอด |
| **int32_t** [GetHashCode](./gethashcode/)() const override | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับชนิดเฉพาะ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์. เปรียบเทียบกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่. เทียบกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบกับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C#. เปิดใช้งานการโคลนประเภทกำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมายค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงหลายตัว |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) รัศมี, หน่วยเป็น pt. ค่าเริ่มต้น – 0 pt. เขียน **double** |
| void [set_Direction](./set_direction/)(**float**) override | ทิศทางของเงา, หน่วยเป็นองศา. ค่าเริ่มต้น – 0 \u00B0 (จากซ้ายไปขวา). เขียน **float** |
| void [set_Distance](./set_distance/)(**double**) override | ระยะห่างของเงาจากอ็อบเจ็กต์, หน่วยเป็น pt. ค่าเริ่มต้น – 0 pt. เขียน **double** |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | การจัดแนวสี่เหลี่ยม. ค่าเริ่มต้น – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/). เขียน [RectangleAlignment](../../aspose.slides/rectanglealignment/) |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | ระบุว่าเงาจะหมุนพร้อมกับรูปร่างหรือไม่. ค่าเริ่มต้น – true. เขียน **bool** |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | แฟกเตอร์สเกลแนวนอน, เป็นเปอร์เซ็นต์ของขนาดเดิม. การสเกลแบบลบทำให้พลิก. ค่าเริ่มต้น – 100 %. เขียน **double** |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | แฟกเตอร์สเกลแนวตั้ง, เป็นเปอร์เซ็นต์ของขนาดเดิม. การสเกลแบบลบทำให้พลิก. ค่าเริ่มต้น – 100 %. เขียน **double** |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | มุมเอียงแนวนอน, หน่วยเป็นองศา. ค่าเริ่มต้น – 0 \u00B0. เขียน **double** |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | มุมเอียงแนวตั้ง, หน่วยเป็นองศา. ค่าเริ่มต้น – 0 \u00B0. เขียน **double** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่ shared). อนุญาตให้เปลี่ยนพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบกับเมธอด [Object.ToString()](../../system/object/tostring/) ของ C#. เปิดใช้งานการแปลงอ็อบเจ็กต์กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IOuterShadow](../ioutershadow/)
* คลาส [IVisualEffect](../ivisualeffect/)
* คลาส [IPVIObject](../../aspose.slides/ipviobject/)
* เนมสเปซ [Aspose::Slides::Effects](../)
* ไลบรารี [Aspose.Slides](../../)