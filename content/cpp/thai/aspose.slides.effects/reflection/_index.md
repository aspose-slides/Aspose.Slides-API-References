---
title: Reflection
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เป็นตัวแทนของเอฟเฟกต์การสะท้อน.
type: docs
weight: 1067
url: /th/aspose.slides.effects/reflection/
---
## Reflection คลาส

เป็นตัวแทนของ [Reflection](./) เอฟเฟกต์.

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## เมธอด

| Method | คำอธิบาย |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | กำหนดว่าค่า [Reflection](./) ที่ระบุเท่ากับ [Reflection](./) ปัจจุบันหรือไม่ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมแบบ C#-style ซึ่ง NaN สองค่าเทียบกันเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมแบบ C#-style สำหรับ double โดยที่ NaN สองค่าเทียบกันเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) รัศมี. อ่านเป็น **double** |
| **float** [get_Direction](./get_direction/)() override | ทิศทางของการสะท้อน. อ่าน **float** |
| **double** [get_Distance](./get_distance/)() override | ระยะทางของการสะท้อน. อ่าน **double** |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | กำหนดตำแหน่งสุดท้าย (ตามแนวลาดของกราเดียนท์อัลฟ่า) ของค่าความทึบสุดท้าย (เปอร์เซ็นต์). อ่าน **float** |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | ความทึบของการสะท้อนสุดท้าย (เปอร์เซ็นต์). อ่าน **float** |
| **float** [get_FadeDirection](./get_fadedirection/)() override | กำหนดทิศทางการย้ายการสะท้อน (มุม). อ่าน **float** |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | คืนค่า parent [IPresentationComponent](../../aspose.slides/ipresentationcomponent/). อ่านอย่างเดียว [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | การจัดแนวสี่เหลี่ยม. อ่าน [RectangleAlignment](../../aspose.slides/rectanglealignment/) |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | กำหนดว่าการสะท้อนควรหมุนพร้อมกับรูปทรงหรือไม่ หากรูปทรงถูกหมุน. อ่าน **bool** |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | กำหนดปัจจัยสเกลแนวนอน, การสเกลเชิงลบทำให้พลิก. (เปอร์เซ็นต์) อ่าน **double** |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | กำหนดปัจจัยสเกลแนวตั้ง, การสเกลเชิงลบทำให้พลิก. (เปอร์เซ็นต์) อ่าน **double** |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | กำหนดมุมเบี่ยงแนวนอน. อ่าน **double** |
| **double** [get_SkewVertical](./get_skewvertical/)() override | กำหนดมุมเบี่ยงแนวตั้ง. อ่าน **double** |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | กำหนดตำแหน่งเริ่มต้น (ตามแนวลาดของกราเดียนท์อัลฟ่า) ของค่าความทึบเริ่มต้น (เปอร์เซ็นต์). อ่าน **float** |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | ความทึบเริ่มต้นของการสะท้อน (เปอร์เซ็นต์). อ่าน **float** |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | เวอร์ชัน. อ่านอย่างเดียว **uint32_t** |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | รับข้อมูลเอฟเฟกต์ [Reflection](./) ที่มีผลโดยใช้การสืบทอด |
| **int32_t** [GetHashCode](./gethashcode/)() const override | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับชนิดหนึ่ง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์. เทียบเท่าการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่. เทียบเท่าตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเท่าการทำงานของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนชนิดที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. ไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสำหรับซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์ตามอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์ตามอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงหลายตัว |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) รัศมี. เขียน **double** |
| void [set_Direction](./set_direction/)(**float**) override | ทิศทางของการสะท้อน. เขียน **float** |
| void [set_Distance](./set_distance/)(**double**) override | ระยะทางของการสะท้อน. เขียน **double** |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | กำหนดตำแหน่งสุดท้าย (ตามแนวลาดของกราเดียนท์อัลฟ่า) ของค่าความทึบสุดท้าย (เปอร์เซ็นต์). เขียน **float** |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | ความทึบของการสะท้อนสุดท้าย (เปอร์เซ็นต์). เขียน **float** |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | กำหนดทิศทางการย้ายการสะท้อน (มุม). เขียน **float** |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | การจัดแนวสี่เหลี่ยม. เขียน [RectangleAlignment](../../aspose.slides/rectanglealignment/) |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | กำหนดว่าการสะท้อนควรหมุนพร้อมกับรูปทรงหรือไม่ หากรูปทรงถูกหมุน. เขียน **bool** |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | กำหนดปัจจัยสเกลแนวนอน, การสเกลเชิงลบทำให้พลิก. (เปอร์เซ็นต์) เขียน **double** |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | กำหนดปัจจัยสเกลแนวตั้ง, การสเกลเชิงลบทำให้พลิก. (เปอร์เซ็นต์) เขียน **double** |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | กำหนดมุมเบี่ยงแนวนอน. เขียน **double** |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | กำหนดมุมเบี่ยงแนวตั้ง. เขียน **double** |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | กำหนดตำแหน่งเริ่มต้น (ตามแนวลาดของกราเดียนท์อัลฟ่า) ของค่าความทึบเริ่มต้น (เปอร์เซ็นต์). เขียน **float** |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | ความทึบเริ่มต้นของการสะท้อน (เปอร์เซ็นต์). เขียน **float** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนการแชร์). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเท่าการทำงานของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็น typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IReflection](../ireflection/)
* คลาส [IVisualEffect](../ivisualeffect/)
* คลาส [IPVIObject](../../aspose.slides/ipviobject/)
* เนมสเปซ [Aspose::Slides::Effects](../)
* ไลบรารี [Aspose.Slides](../../)