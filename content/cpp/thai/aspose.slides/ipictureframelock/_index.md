---
title: IPictureFrameLock
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดว่าการดำเนินการใดถูกปิดใช้งานบน PictureFrameEx พาเรนต์.
type: docs
weight: 3264
url: /th/aspose.slides/ipictureframelock/
---
## IPictureFrameLock คลาส


Determines which operations are disabled on the parent PictureFrameEx.

```cpp
class IPictureFrameLock : public virtual Aspose::Slides::IBaseShapeLock
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดทศนิยมแบบ C#-style ที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากันแม้ว่า ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดทศนิยมแบบ C#-style ที่ NaN สองค่าได้รับการพิจารณาว่าเท่ากันแม้ว่า ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อใช้ภายในเท่านั้น. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | กำหนดว่าการเปลี่ยนค่า adjust ถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | กำหนดว่าการเปลี่ยน arrowheads ถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | กำหนดว่ารูปร่างต้องคงอัตราส่วนภาพเมื่อปรับขนาดหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_CropLocked](./get_croplocked/)() | กำหนดว่าการตัดภาพถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | กำหนดว่าการเปลี่ยนแปลงโดยตรงของคอนทัวร์ของรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | กำหนดว่าการเพิ่มรูปร่างนี้ไปยังกลุ่มถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | คืนค่า true ถ้าธงล็อกทั้งหมดถูกปิดใช้งาน อ่านอย่างเดียว **bool**. |
| virtual **bool** [get_PositionLocked](./get_positionlocked/)() | กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_RotationLocked](./get_rotationlocked/)() | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นคล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. คล้ายกับตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นคล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). ทำให้สามารถโคลนชนิดที่กำหนดเองได้. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริงๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์มอบหมายค่า. จริงๆ ไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | อ้างอิงเปรียบเทียบอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การนิยามเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การนิยามเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่ใช้ร่วมโดยค่าที่ระบุ. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | กำหนดว่าการเปลี่ยนค่า adjust ถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | กำหนดว่าการเปลี่ยน arrowheads ถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | กำหนดว่ารูปร่างต้องคงอัตราส่วนภาพเมื่อปรับขนาดหรือไม่ เขียน **bool**. |
| virtual void [set_CropLocked](./set_croplocked/)(**bool**) | กำหนดว่าการตัดภาพถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | กำหนดว่าการเปลี่ยนแปลงโดยตรงของคอนทัวร์ของรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | กำหนดว่าการเพิ่มรูปร่างนี้ไปยังกลุ่มถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_PositionLocked](./set_positionlocked/)(**bool**) | กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_RotationLocked](./set_rotationlocked/)(**bool**) | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์แม่แบบที่ n ให้เป็น weak pointer (แทน shared). อนุญาตให้สลับ pointer ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วม. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่ใช้ร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงที่ใช้ร่วม. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). ทำให้แปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) sentry. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับ weak reference. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector แทน. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [IBaseShapeLock](../ibaseshapelock/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)