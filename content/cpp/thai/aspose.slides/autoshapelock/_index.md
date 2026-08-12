---
title: AutoShapeLock
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: กำหนดว่าการทำงานใดบ้างที่ถูกปิดใช้งานบน AutoshapeEx พาเรนต์
type: docs
weight: 79
url: /th/aspose.slides/autoshapelock/
---
## AutoShapeLock คลาส

กำหนดว่าการทำงานใดบ้างที่ถูกปิดใช้งานบน AutoshapeEx พาเรนท์

```cpp
class AutoShapeLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IAutoShapeLock
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้การทำงานของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ชนิดอ้างอิงในสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ชนิดค่าในสไตล์ของ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่สองค่า NaN ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 ค่า NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบเลขทศนิยมสไตล์ C# ที่สองค่า NaN ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 ค่า NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้สำหรับวัตถุประสงค์ภายในเท่านั้น |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | กำหนดว่าการเปลี่ยนแปลงค่าการปรับนั้นถูกห้ามหรือไม่ อ่าน **bool** |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | กำหนดว่าการเปลี่ยนหัวลูกศรนั้นถูกห้ามหรือไม่ อ่าน **bool** |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | กำหนดว่ารูปร่างต้องรักษาอัตราส่วนภาพเมื่อตรวจขนาดหรือไม่ อ่าน **bool** |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | กำหนดว่าการเปลี่ยนรูปร่างโดยตรงของคอนทัวร์นี้ถูกห้ามหรือไม่ อ่าน **bool** |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | กำหนดว่าการเพิ่มรูปร่างนี้เข้าไปในกลุ่มถูกห้ามหรือไม่ อ่าน **bool** |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | คืนค่า true ถ้ารหัสล็อกทั้งหมดถูกปิดใช้งาน อ่านอย่างเดียว **bool** |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool** |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool** |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool** |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | กำหนดว่าการเปลี่ยนประเภทของรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool** |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | กำหนดว่าการตรวจขนาดรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool** |
| **bool** [get_TextLocked](./get_textlocked/)() override | กำหนดว่าการแก้ไขข้อความถูกห้ามหรือไม่ อ่าน **bool** |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเท่ากับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์ที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์. เทียบเท่ากับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแทนซ์ของชนิดที่อธิบายโดย targetType หรือไม่. เทียบเท่ากับออปเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเท่ากับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสืบทอดสำเนาในซับคลาส |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการสืบทอดสำเนาในซับคลาส |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ชนิดค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเฉพาะเจาะจงของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงหลายค่า |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | กำหนดว่าการเปลี่ยนแปลงค่าการปรับนั้นถูกห้ามหรือไม่. เขียน **bool** |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | กำหนดว่าการเปลี่ยนหัวลูกศรนั้นถูกห้ามหรือไม่. เขียน **bool** |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | กำหนดว่ารูปร่างต้องรักษาอัตราส่วนภาพเมื่อตรวจขนาดหรือไม่. เขียน **bool** |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | กำหนดว่าการเปลี่ยนรูปร่างโดยตรงของคอนทัวร์นี้ถูกห้ามหรือไม่. เขียน **bool** |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | กำหนดว่าการเพิ่มรูปร่างนี้เข้าไปในกลุ่มถูกห้ามหรือไม่. เขียน **bool** |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่. เขียน **bool** |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่. เขียน **bool** |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่. เขียน **bool** |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | กำหนดว่าการเปลี่ยนประเภทของรูปร่างนี้ถูกห้ามหรือไม่. เขียน **bool** |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | กำหนดว่าการตรวจขนาดรูปร่างนี้ถูกห้ามหรือไม่. เขียน **bool** |
| void [set_TextLocked](./set_textlocked/)(**bool**) override | กำหนดว่าการแก้ไขข้อความถูกห้ามหรือไม่. เขียน **bool** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่า argument ที่ n ของเทมเพลตเป็น weak pointer (แทนที่จะเป็น shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่นั้นให้ใช้ smart pointer หรือ ThisProtector |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; แทนที่นั้นให้ใช้ smart pointer หรือ ThisProtector |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเท่ากับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่นั้นให้ใช้ smart pointer หรือ ThisProtector |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่นั้นให้ใช้ smart pointer หรือ ThisProtector |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [BaseShapeLock](../baseshapelock/)
* คลาส [IAutoShapeLock](../iautoshapelock/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)