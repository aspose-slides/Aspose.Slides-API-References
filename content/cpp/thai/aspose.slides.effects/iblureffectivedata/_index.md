---
title: IBlurEffectiveData
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: อ็อบเจกต์ไม่เปลี่ยนแปลงที่แสดงถึงเอฟเฟกต์เบลอที่ถูกนำไปใช้กับรูปทรงทั้งหมดรวมถึงการเติมสีของมัน ทุกช่องสีรวมถึงแอลฟ่าได้รับผลกระทบ.
type: docs
weight: 469
url: /th/aspose.slides.effects/iblureffectivedata/
---
## IBlurEffectiveData คลาส

อ็อบเจกต์ไม่เปลี่ยนแปลงที่แสดงถึงเอฟเฟกต์ [Blur](../blur/) ที่ถูกนำไปใช้กับรูปร่างทั้งหมดรวมถึงการเติมสีของมัน ทุกช่องสีรวมถึงแอลฟ่าได้รับผลกระทบ

```cpp
class IBlurEffectiveData : public virtual Aspose::Slides::Effects::IEffectEffectiveData
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงสไตล์ C# ที่ NaN สองค่าถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual **bool** [get_Grow](./get_grow/)() | กำหนดว่าขอบเขตของอ็อบเจกต์ควรขยายจากการเบลอหรือไม่ ค่า true หมายถึงขอบเขตถูกขยาย ส่วน false หมายถึงไม่ขยาย อ่านอย่างเดียว **bool**. |
| virtual **double** [get_Radius](./get_radius/)() | คืนค่าอัตราการเบลอ อ่านอย่างเดียว **double**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | อานะล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจกต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจกต์. อานะล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType หรือไม่. อานะล็อกของโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | อานะล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนประเภทที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจกต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมโดยค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอากิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | อานะล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้สามารถแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IEffectEffectiveData](../ieffecteffectivedata/)
* เนมสเปซ [Aspose::Slides::Effects](../)
* Library [Aspose.Slides](../../)