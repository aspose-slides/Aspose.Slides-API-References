---
title: IGroupShapeLock
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดว่าการดำเนินการใดบ้างถูกปิดใช้งานบน GroupShape พาเรนท์
type: docs
weight: 2497
url: /th/aspose.slides/igroupshapelock/
---
## IGroupShapeLock คลาส

กำหนดว่าปฏิบัติการใดถูกปิดใช้งานบนพาเรนท์ [GroupShape](../groupshape/).

```cpp
class IGroupShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่า floating point แบบ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับใช้ภายในเท่านั้น. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | กำหนดว่ารูปทรงต้องรักษาอัตราส่วนเมื่อปรับขนาดหรือไม่. อ่าน **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | กำหนดว่าการเพิ่มรูปทรงนี้เข้าไปในกลุ่มถูกห้ามหรือไม่. อ่าน **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | คืนค่า true หากแฟล็กการล็อกทั้งหมดถูกปิด. อ่านอย่างเดียว **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | กำหนดว่าการย้ายรูปทรงนี้ถูกห้ามหรือไม่. อ่าน **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปทรงนี้ถูกห้ามหรือไม่. อ่าน **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | กำหนดว่าการเลือกรูปทรงนี้ถูกห้ามหรือไม่. อ่าน **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | กำหนดว่าการปรับขนาดรูปทรงนี้ถูกห้ามหรือไม่. อ่าน **bool**. |
| virtual **bool** [get_UngroupingLocked](./get_ungroupinglocked/)() | กำหนดว่าการแบ่งรูปกลุ่มนี้ถูกห้ามหรือไม่. อ่าน **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับข้อมูลโครงสร้างตัวนับอ้างอิงที่เชื่อมกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจกต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เทียบกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เทียบกับโอเปอร์เอเตอร์ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา. ไม่ได้คัดลอกอะไรเลย, เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรเลย, เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการสร้างสำเนาสำหรับคลาสย่อย. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายตัว. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าเคานท์อ้างอิงที่ใช้ร่วมกันตามค่าที่ระบุ. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | กำหนดว่ารูปทรงต้องรักษาอัตราส่วนเมื่อปรับขนาดหรือไม่. เขียน **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | กำหนดว่าการเพิ่มรูปทรงนี้เข้าไปในกลุ่มถูกห้ามหรือไม่. เขียน **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | กำหนดว่าการย้ายรูปทรงนี้ถูกห้ามหรือไม่. เขียน **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปทรงนี้ถูกห้ามหรือไม่. เขียน **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | กำหนดว่าการเลือกรูปทรงนี้ถูกห้ามหรือไม่. เขียน **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | กำหนดว่าการปรับขนาดรูปทรงนี้ถูกห้ามหรือไม่. เขียน **bool**. |
| virtual void [set_UngroupingLocked](./set_ungroupinglocked/)(**bool**) | กำหนดว่าการแบ่งรูปกลุ่มนี้ถูกห้ามหรือไม่. เขียน **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า template argument ตัวที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของเคานท์อ้างอิงที่ใช้ร่วมกัน. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าเคานท์อ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่าเคานท์อ้างอิงที่ใช้ร่วมกัน. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่คล้าย C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าเคานท์ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าเคานท์ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointer หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [IBaseShapeLock](../ibaseshapelock/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)