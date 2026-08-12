---
title: AlphaModulateFixed
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงถึงเอฟเฟ็กต์ Alpha Modulate Fixed ค่าตัวแปรอัลฟา (ความทึบ) จะถูกคูณด้วยเปอร์เซ็นต์คงที่
type: docs
weight: 66
url: /th/aspose.slides.effects/alphamodulatefixed/
---
## AlphaModulateFixed คลาส

Represents an Alpha Modulate Fixed effect. Effect alpha (opacity) values are multiplied by a fixed percentage.

```cpp
class AlphaModulateFixed : public Aspose::Slides::Effects::ImageTransformOperation,
                           public Aspose::Slides::Effects::IAlphaModulateFixed,
                           public Aspose::Slides::Effects::IVisualEffect
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | ระบุว่า [AlphaModulateFixed](./) ที่ระบุเทียบกับ [AlphaModulateFixed](./) ปัจจุบันเท่ากันหรือไม่ |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถือว่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| **float** [get_Amount](./get_amount/)() override | ส่งกลับค่าผลกระทบเป็นเปอร์เซ็นต์ อ่านแบบ **float** |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../../aspose.slides/idomobject/)\> [get_Parent_Immediate](../../aspose.slides/idomobject/get_parent_immediate/)() | ส่งกลับอ็อบเจ็กต์ Parent_Immediate อ่านอย่างเดียว [IDOMObject](../../aspose.slides/idomobject/) |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | ส่งกลับ [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) พาเรนต์ อ่านอย่างเดียว [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เกี่ยวข้องกับอ็อบเจ็กต์ |
| [System::SharedPtr](../../system/sharedptr/)\<[IAlphaModulateFixedEffectiveData](../ialphamodulatefixedeffectivedata/)\> [GetEffective](./geteffective/)() override | รับข้อมูลเอฟเฟ็กต์ Alpha Modulate Fixed ที่มีผลโดยนำการสืบทอดมาใช้ |
| **int32_t** [GetHashCode](./gethashcode/)() const override | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับชนิดเฉพาะ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทที่แท้จริงของอ็อบเจ็กต์ ตรงกับการเรียก [System.Object.GetType()](../../system/object/gettype/) ของ C# |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ ตรงกับโอเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | ตรงกับเมธอด [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ของ C# เปิดใช้การคัดลอกประเภทที่กำหนดเอง |
| [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกในคลาสย่อย |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์มอบหมาย ไม่ได้คัดลอกอะไรจริงๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้การคัดลอกในคลาสย่อย |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์ตามอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์ตามอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การปรับพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การปรับพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงร่วมโดยค่าที่กำหนด |
| void [set_Amount](./set_amount/)(**float**) override | ส่งกลับค่าผลกระทบเป็นเปอร์เซ็นต์ เขียนเป็น **float** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์ template ที่ n เป็น weak pointer (แทน shared) ให้เปลี่ยน pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งค่าตัวนับอ้างอิงร่วม ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | ต่อจากเมธอด [Object.ToString()](../../system/object/tostring/) ของ C# เปิดใช้การแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ตาม construct typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับอ้างอิง weak ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับอ้างอิง weak ไม่ควรเรียกโดยตรง ใช้ smart pointer หรือ ThisProtector แทน |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../../aspose.slides/pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## ดูเพิ่มเติม

* คลาส [ImageTransformOperation](../imagetransformoperation/)
* คลาส [IAlphaModulateFixed](../ialphamodulatefixed/)
* คลาส [IVisualEffect](../ivisualeffect/)
* เนมสเปซ [Aspose::Slides::Effects](../)
* ไลบรารี [Aspose.Slides](../../)