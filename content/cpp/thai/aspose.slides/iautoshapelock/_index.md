---
title: IAutoShapeLock
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: กำหนดว่าการดำเนินการใดบ้างถูกปิดใช้งานบน AutoshapeEx พาเรนต์
type: docs
weight: 1379
url: /th/aspose.slides/iautoshapelock/
---
## IAutoShapeLock คลาส


Determines which operations are disabled on the parent AutoshapeEx.

```cpp
class IAutoShapeLock : public virtual Aspose::Slides::IBaseShapeLock
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C# ที่ถือว่า NaN สองค่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | กำหนดว่าการเปลี่ยนค่า adjust ถูกห้ามหรือไม่ อ่าน **bool** |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | กำหนดว่าการเปลี่ยน arrowheads ถูกห้ามหรือไม่ อ่าน **bool** |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | กำหนดว่ารูปร่างต้องคงอัตราส่วนเมื่อปรับขนาดหรือไม่ อ่าน **bool** |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | กำหนดว่าการเปลี่ยนรูปร่างของคอนทัวร์โดยตรงของรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool** |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | กำหนดว่าการเพิ่มรูปร่างนี้เข้าไปในกลุ่มถูกห้ามหรือไม่ อ่าน **bool** |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | คืนค่า true หากทุก lock-flag ถูกปิดใช้งาน อ่านอย่างเดียว **bool** |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool** |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool** |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool** |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่ อ่าน **bool** |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool** |
| virtual **bool** [get_TextLocked](./get_textlocked/)() | กำหนดว่าการแก้ไขข้อความถูกห้ามหรือไม่ อ่าน **bool** |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับข้อมูลโครงสร้างตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับออเปอร์เรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ตามคำสั่ง lock() ของ C# เพื่อทำการล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการทำสำเนาประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. ไม่ได้คัดลอกอะไรเลย จริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาของซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสร้างสำเนาของซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงวัตถุประเภทค่ากับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงร่วมโดยค่าที่กำหนด |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | กำหนดว่าการเปลี่ยนค่า adjust ถูกห้ามหรือไม่ เขียน **bool** |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | กำหนดว่าการเปลี่ยน arrowheads ถูกห้ามหรือไม่ เขียน **bool** |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | กำหนดว่ารูปร่างต้องคงอัตราส่วนเมื่อปรับขนาดหรือไม่ เขียน **bool** |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | กำหนดว่าการเปลี่ยนรูปร่างของคอนทัวร์โดยตรงของรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool** |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | กำหนดว่าการเพิ่มรูปร่างนี้เข้าไปในกลุ่มถูกห้ามหรือไม่ เขียน **bool** |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool** |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool** |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool** |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่ เขียน **bool** |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool** |
| virtual void [set_TextLocked](./set_textlocked/)(**bool**) | กำหนดว่าการแก้ไขข้อความถูกห้ามหรือไม่ เขียน **bool** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่จะเป็น shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าตัวนับอ้างอิงร่วมและคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ตาม construct typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## ดูเพิ่มเติม

* คลาส [IBaseShapeLock](../ibaseshapelock/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)