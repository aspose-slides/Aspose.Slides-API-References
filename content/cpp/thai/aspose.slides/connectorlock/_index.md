---
title: ConnectorLock
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: กำหนดว่าการดำเนินการใดบ้างที่ถูกปิดใช้งานบนพาเรนท์ Connector.
type: docs
weight: 495
url: /th/aspose.slides/connectorlock/
---
## ConnectorLock คลาส

กำหนดว่าการดำเนินการใดบ้างที่ถูกปิดใช้งานบนพาเรนท์ [Connector](../connector/).

```cpp
class ConnectorLock : public Aspose::Slides::BaseShapeLock,
                      public Aspose::Slides::IConnectorLock
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้หลักการของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C# ที่ NaN สองค่า ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบค่าจุดลอยแบบ C# ที่ NaN สองค่า ถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| **bool** [get_AdjustHandlesLocked](./get_adjusthandleslocked/)() override | กำหนดว่าการเปลี่ยนค่า adjust ถูกห้ามหรือไม่ อ่าน **bool**. |
| **bool** [get_ArrowheadsLocked](./get_arrowheadslocked/)() override | กำหนดว่าการเปลี่ยนหัวลูกศรถูกห้ามหรือไม่ อ่าน **bool**. |
| **bool** [get_AspectRatioLocked](./get_aspectratiolocked/)() override | กำหนดว่ารูปร่างต้องคงอัตราส่วนเดิมขณะปรับขนาดหรือไม่ อ่าน **bool**. |
| **bool** [get_EditPointsLocked](./get_editpointslocked/)() override | กำหนดว่าการเปลี่ยนแป้นรูปโดยตรงของรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool**. |
| **bool** [get_GroupingLocked](./get_groupinglocked/)() override | กำหนดว่าการเพิ่มรูปร่างนี้เข้าไปในกลุ่มถูกห้ามหรือไม่ อ่าน **bool**. |
| **bool** [get_NoLocks](../baseshapelock/get_nolocks/)() override | คืนค่า true หากแฟล็กล็อคทั้งหมดถูกปิดใช้งาน อ่านอย่างเดียว **bool**. |
| **bool** [get_PositionMove](./get_positionmove/)() override | กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool**. |
| **bool** [get_RotateLocked](./get_rotatelocked/)() override | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool**. |
| **bool** [get_SelectLocked](./get_selectlocked/)() override | กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool**. |
| **bool** [get_ShapeTypeLocked](./get_shapetypelocked/)() override | กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่ อ่าน **bool**. |
| **bool** [get_SizeLocked](./get_sizelocked/)() override | กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่ อ่าน **bool**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลเคาน์เตอร์อ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเคียงเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชอ็อบเจกต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เทียบเคียงการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เทียบเคียงตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเคียงเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการโคลนประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยการอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงของอ็อบเจกต์ประเภทค่ากับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนเคาน์เตอร์อ้างอิงที่แชร์โดยค่าที่ระบุ. |
| void [set_AdjustHandlesLocked](./set_adjusthandleslocked/)(**bool**) override | กำหนดว่าการเปลี่ยนค่า adjust ถูกห้ามหรือไม่ เขียน **bool**. |
| void [set_ArrowheadsLocked](./set_arrowheadslocked/)(**bool**) override | กำหนดว่าการเปลี่ยนหัวลูกศรถูกห้ามหรือไม่ เขียน **bool**. |
| void [set_AspectRatioLocked](./set_aspectratiolocked/)(**bool**) override | กำหนดว่ารูปร่างต้องคงอัตราส่วนเดิมขณะปรับขนาดหรือไม่ เขียน **bool**. |
| void [set_EditPointsLocked](./set_editpointslocked/)(**bool**) override | กำหนดว่าการเปลี่ยนแป้นรูปโดยตรงของรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool**. |
| void [set_GroupingLocked](./set_groupinglocked/)(**bool**) override | กำหนดว่าการเพิ่มรูปร่างนี้เข้าไปในกลุ่มถูกห้ามหรือไม่ เขียน **bool**. |
| void [set_PositionMove](./set_positionmove/)(**bool**) override | กำหนดว่าการย้ายรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool**. |
| void [set_RotateLocked](./set_rotatelocked/)(**bool**) override | กำหนดว่าการเปลี่ยนมุมการหมุนของรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool**. |
| void [set_SelectLocked](./set_selectlocked/)(**bool**) override | กำหนดว่าการเลือกรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool**. |
| void [set_ShapeTypeLocked](./set_shapetypelocked/)(**bool**) override | กำหนดว่าการเปลี่ยนประเภทของรูปร่างถูกห้ามหรือไม่ เขียน **bool**. |
| void [set_SizeLocked](./set_sizelocked/)(**bool**) override | กำหนดว่าการปรับขนาดรูปร่างนี้ถูกห้ามหรือไม่ เขียน **bool**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่จะแชร์). อนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของเคาน์เตอร์อ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนเคาน์เตอร์อ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่นั้นให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนเคาน์เตอร์อ้างอิงที่แชร์และคืนค่า. ไม่ควรเรียกโดยตรง; แทนที่นั้นให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเคียงเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำงานตามโครงสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนเคาน์เตอร์อ้างอิง weak. ไม่ควรเรียกโดยตรง; แทนที่นั้นให้ใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนเคาน์เตอร์อ้างอิง weak. ไม่ควรเรียกโดยตรง; แทนที่นั้นให้ใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [BaseShapeLock](../baseshapelock/)
* คลาส [IConnectorLock](../iconnectorlock/)
* เนมสเปซ [Aspose::Slides](../)
* ไลบรารี [Aspose.Slides](../../)