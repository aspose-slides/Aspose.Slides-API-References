---
title: IBlur
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงถึงเอฟเฟกต์ Blur ที่ใช้กับรูปทรงทั้งหมดรวมถึงการเติมสี ทั้งช่องสีรวมถึงอัลฟ่าได้รับผลกระทบ.
type: docs
weight: 456
url: /th/aspose.slides.effects/iblur/
---
## IBlur คลาส

แสดงถึงเอฟเฟกต์ [Blur](../blur/) ที่ใช้กับรูปทรงทั้งหมดรวมถึงการเติม สีทุกช่องรวมถึงอัลฟ่าได้รับผลกระทบ

```cpp
class IBlur : public virtual Aspose::Slides::Effects::IImageTransformOperation,
              public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IBlurEffectiveData>>
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยในสไตล์ C# ที่ NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยในสไตล์ C# ที่ NaN สองค่าถูกถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับภายในเท่านั้น |
| virtual **bool** [get_Grow](./get_grow/)() | กำหนดว่าขอบเขตของอ็อบเจกต์ควรขยายเนื่องจากการเบลอหรือไม่ ค่าจริงบ่งชี้ว่าขอบเขตถูกขยายและค่าผิดบ่งชี้ว่าไม่ได้ขยาย อ่าน **bool** |
| virtual **double** [get_Radius](./get_radius/)() | ส่งคืนรัศมีการเบลอ อ่าน **double** |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์ |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | รับข้อมูลที่มีผลโดยใช้การสืบทอด |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | มีลักษณะคล้ายเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจกต์แบบกำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์ มีลักษณะคล้ายการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่ targetType อธิบายหรือไม่ มีลักษณะคล้ายโอเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุตรวจสอบ [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | มีลักษณะคล้ายเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์ กำหนดค่าโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์คัดลอก ไม่ได้คัดลอกจริง ๆ เพียงกำหนดอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกจริง ๆ เพียงกำหนดอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจกต์ประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การทำเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การทำเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์โดยค่าที่ระบุ |
| virtual void [set_Grow](./set_grow/)(**bool**) | กำหนดว่าขอบเขตของอ็อบเจกต์ควรขยายเนื่องจากการเบลอหรือไม่ ค่าจริงบ่งชี้ว่าขอบเขตถูกขยายและค่าผิดบ่งชี้ว่าไม่ได้ขยาย เขียน **bool** |
| virtual void [set_Radius](./set_radius/)(**double**) | ตั้งรัศมีการเบลอ เขียน **double** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาเรย์เทมเพลตที่ n เป็น weak pointer (แทน shared) อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและส่งคืนจำนวนการอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | มีลักษณะคล้ายเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจกต์แบบกำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่เป็นโครงสร้าง C# typeof([System.Object](../../system/object/)) |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง C# lock() เรียกโดยตรงหรือใช้วัตถุตรวจสอบ [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## ดูเพิ่มเติม

* คลาส [IImageTransformOperation](../iimagetransformoperation/)
* คลาส [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* เนมสเปซ [Aspose::Slides::Effects](../)
* ไลบรารี [Aspose.Slides](../../)