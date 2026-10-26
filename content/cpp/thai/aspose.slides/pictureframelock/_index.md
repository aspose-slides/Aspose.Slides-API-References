---
title: PictureFrameLock
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดว่าการดำเนินการใดบ้างถูกปิดใช้งานบน PictureFrame พาเรนต์
type: docs
weight: 4746
url: /th/aspose.slides/pictureframelock/
---
## PictureFrameLock คลาส

กำหนดการดำเนินการที่ถูกปิดใช้งานบนพาเรนต์ [PictureFrame](../pictureframe/).

```cpp
class PictureFrameLock : public Aspose::Slides::BaseShapeLock,
                         public Aspose::Slides::IPictureFrameLock
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ C# [Object.Equals](../../system/object/equals/) ความหมาย. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | กำหนดว่าการเปลี่ยนค่า adjust ถูกห้ามหรือไม่. อ่าน **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | กำหนดว่าการเปลี่ยน arrowheads ถูกห้ามหรือไม่. อ่าน **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | กำหนดว่ารูปต้องรักษาอัตราส่วนภาพเมื่อปรับขนาดหรือไม่. อ่าน **bool**. |
| **bool** [get_CropLocked](./get_croplocked/)() override | กำหนดว่าการครอบตัดภาพถูกห้ามหรือไม่. อ่าน **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | กำหนดว่าการเปลี่ยนขอบของรูปโดยตรงถูกห้ามหรือไม่. อ่าน **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | กำหนดว่าการเพิ่มรูปนี้เข้าไปในกลุ่มถูกห้ามหรือไม่. อ่าน **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | คืนค่า true หากธงล็อกทั้งหมดถูกปิดใช้งาน. อ่านอย่างเดียว **bool**. |
| **bool** [get_PositionLocked](./get_positionlocked/)() override | กำหนดว่าการย้ายรูปนี้ถูกห้ามหรือไม่. อ่าน **bool**. |
| **bool** [get_RotationLocked](./get_rotationlocked/)() override | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปนี้ถูกห้ามหรือไม่. อ่าน **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | กำหนดว่าการเลือกรูปนี้ถูกห้ามหรือไม่. อ่าน **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | กำหนดว่าการเปลี่ยนประเภทรูปถูกห้ามหรือไม่. อ่าน **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | กำหนดว่าการปรับขนาดรูปนี้ถูกห้ามหรือไม่. อ่าน **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลเคาน์เตอร์อ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอนาล็อกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจกต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นอนาล็อกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอนาล็อกของโอเปอเรเตอร์ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอนาล็อกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | อ็อพเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าเคาน์เตอร์อ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | กำหนดว่าการเปลี่ยนค่า adjust ถูกห้ามหรือไม่. เขียน **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | กำหนดว่าการเปลี่ยน arrowheads ถูกห้ามหรือไม่. เขียน **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | กำหนดว่ารูปต้องรักษาอัตราส่วนภาพเมื่อปรับขนาดหรือไม่. เขียน **bool**. |
| void [set_CropLocked](./set_croplocked/)(**bool**) override | กำหนดว่าการครอบตัดภาพถูกห้ามหรือไม่. เขียน **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | กำหนดว่าการเปลี่ยนขอบของรูปโดยตรงถูกห้ามหรือไม่. เขียน **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | กำหนดว่าการเพิ่มรูปนี้เข้าไปในกลุ่มถูกห้ามหรือไม่. เขียน **bool**. |
| void [set_PositionLocked](./set_positionlocked/)(**bool**) override | กำหนดว่าการย้ายรูปนี้ถูกห้ามหรือไม่. เขียน **bool**. |
| void [set_RotationLocked](./set_rotationlocked/)(**bool**) override | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปนี้ถูกห้ามหรือไม่. เขียน **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | กำหนดว่าการเลือกรูปนี้ถูกห้ามหรือไม่. เขียน **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | กำหนดว่าการเปลี่ยนประเภทรูปถูกห้ามหรือไม่. เขียน **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | กำหนดว่าการปรับขนาดรูปนี้ถูกห้ามหรือไม่. เขียน **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนการแชร์). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของเคาน์เตอร์อ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าเคาน์เตอร์อ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดค่าและคืนค่าเคาน์เตอร์อ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอนาล็อกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามคำสั่ง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มค่าเคาน์เตอร์อ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดค่าเคาน์เตอร์อ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [BaseShapeLock](../baseshapelock/)
* คลาส [IPictureFrameLock](../ipictureframelock/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)