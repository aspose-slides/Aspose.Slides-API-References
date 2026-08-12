---
title: IConnectorLock
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดว่าการดำเนินการใดถูกปิดใช้งานบนพาเรนต์ Connector.
type: docs
weight: 1860
url: /th/aspose.slides/iconnectorlock/
---
## IConnectorLock คลาส

กำหนดว่าการดำเนินการใดถูกปิดใช้งานบนพาเรนต์ [Connector](../connector/).

```cpp
class IConnectorLock : public virtual Aspose::Slides::IBaseShapeLock
```

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้เซมานติกของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในรูปแบบ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในรูปแบบ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# โดยที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 นั้น NaN จะไม่เท่ากับค่าตัวใดเลย รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# โดยที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตามมาตรฐาน IEC 60559:1989 นั้น NaN จะไม่เท่ากับค่าตัวใดเลย รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| virtual **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() | กำหนดว่าการเปลี่ยนค่า adjust ถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() | กำหนดว่าการเปลี่ยนหัวลูกศรถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() | กำหนดว่ารูปร่างต้องรักษาอัตราส่วนเมื่อปรับขนาดหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_EditPointsLocked](./get_editpointslocked/)() | กำหนดว่าการเปลี่ยนรูปโครงร่างโดยตรงของรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_GroupingLocked](./get_groupinglocked/)() | กำหนดว่าการเพิ่มรูปร่างนี้เข้าไปในกลุ่มถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_NoLocks](../ibaseshapelock/get_nolocks/)() | คืนค่า true หากล็อก-ฟล็อกทั้งหมดถูกปิดใช้งาน อ่านอย่างเดียว **bool**. |
| virtual **bool** [get_PositionMove](./get_positionmove/)() | กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_RotateLocked](./get_rotatelocked/)() | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_SelectLocked](./get_selectlocked/)() | กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() | กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่ อ่าน **bool**. |
| virtual **bool** [get_SizeLocked](./get_sizelocked/)() | กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลเคาน์เตอร์อ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นอะแนโลกของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของอ็อบเจ็กต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจ็กต์. เป็นอะแนโลกของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอะแนโลกของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# สำหรับการล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นอะแนโลกของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทแบบกำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอ้อะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอ้อะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | อ้างอิง-เปรียบเทียบอ็อบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การเชี่ยวชาญของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การเชี่ยวชาญของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนเคาน์เตอร์อ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) | กำหนดว่าการเปลี่ยนค่า adjust ถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) | กำหนดว่าการเปลี่ยนหัวลูกศรถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) | กำหนดว่ารูปร่างต้องรักษาอัตราส่วนเมื่อปรับขนาดหรือไม่ เขียน **bool**. |
| virtual void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) | กำหนดว่าการเปลี่ยนรูปโครงร่างโดยตรงของรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_GroupingLocked](./set_groupinglocked/)(**bool**) | กำหนดว่าการเพิ่มรูปร่างนี้เข้าไปในกลุ่มถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_PositionMove](./set_positionmove/)(**bool**) | กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_RotateLocked](./set_rotatelocked/)(**bool**) | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_SelectLocked](./set_selectlocked/)(**bool**) | กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) | กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [set_SizeLocked](./set_sizelocked/)(**bool**) | กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่เป็น shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของเคาน์เตอร์อ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มเคาน์เตอร์อ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าเคาน์เตอร์อ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นอะแนโลกของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# สำหรับการปลดล็อก. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มเคาน์เตอร์อ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดเคาน์เตอร์อ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [IBaseShapeLock](../ibaseshapelock/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)