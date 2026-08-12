---
title: IRotation3D
second_title: Aspose.Slides สำหรับ C++ API Reference
description: แสดงการหมุน 3 มิติของแผนภูมิ
type: docs
weight: 1171
url: /th/aspose.slides.charts/irotation3d/
---
## IRotation3D คลาส


Represents 3D rotation of a chart.

```cpp
class IRotation3D : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็เจ็กต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็เจ็กต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C#-style ที่ NaN สองค่าได้รับการถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจริงแบบ C#-style ที่ NaN สองค่าได้รับการถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| virtual **uint16_t** [get_DepthPercents](./get_depthpercents/)() | คืนค่าความลึกของแผนภูมิ 3D เป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 20 ถึง 2000 เปอร์เซ็นต์) อ่าน **uint16_t**. |
| virtual **uint16_t** [get_HeightPercents](./get_heightpercents/)() | ระบุความสูงของแผนภูมิ 3-D เป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 5 ถึง 500 เปอร์เซ็นต์) อ่าน **uint16_t**. |
| virtual **uint8_t** [get_Perspective](./get_perspective/)() | คืนค่าเปอร์เซ็นต์มุมมอง (field of view angle) สำหรับแผนภูมิ 3D (ระหว่าง 0 ถึง 100) จะถูกละเว้นหากค่า RightAngleAxes เป็น true. อ่าน **uint8_t**. |
| virtual **bool** [get_RightAngleAxes](./get_rightangleaxes/)() | กำหนดว่าแกนของแผนภูมิอยู่ในมุมฉากหรือไม่ แทนที่จะวาดในมุมมองเชิงลึก กล่าวคือกำหนดว่ามุมของแกนแผนภูมิมีอิสระจากการหมุนหรือการยกของแผนภูมิหรือไม่ อ่าน **bool**. |
| virtual **int8_t** [get_RotationX](./get_rotationx/)() | คืนค่ามุมการหมุนรอบแกน X (คือในทิศทาง Y สำหรับแผนภูมิ 3D) (ระหว่าง -90 ถึง 90 องศา) คุณสมบัตินี้สอดคล้องกับรายการ rotX (X Rotation) ใน ECMA-376 และตัวเลือก “Y Rotation” ใน PowerPoint 2007+ อ่าน **int8_t**. |
| virtual **uint16_t** [get_RotationY](./get_rotationy/)() | คืนค่ามุมการหมุนรอบแกน Y (คือในทิศทาง X สำหรับแผนภูมิ 3D) (ระหว่าง 0 ถึง 360 องศา) คุณสมบัตินี้สอดคล้องกับรายการ rotY (Y Rotation) ใน ECMA-376 และตัวเลือก “X Rotation” ใน PowerPoint 2007+ อ่าน **uint16_t**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog of C# [Object.GetHashCode()](../../system/object/gethashcode/) method. Enables hashing of custom objects. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์ Analog of C# [System.Object.GetType()](../../system/object/gettype/) call. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ Analog of C# 'is' operator. |
| void [Lock](../../system/object/lock/)() | Implements C# lock() statement locking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog of C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) method. Enables cloning custom types. |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy constructor. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment operator. Doesn't copy anything, really, just initializes new object and enables copy constructing subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ string และ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของ strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดค่าตัวนับอ้างอิงที่แชร์โดยค่าที่ระบุ. |
| virtual void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) | ตั้งค่าความลึกของแผนภูมิ 3D เป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 20 ถึง 2000 เปอร์เซ็นต์) Write **uint16_t**. |
| virtual void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) | ระบุความสูงของแผนภูมิ 3-D เป็นเปอร์เซ็นต์ของความกว้างแผนภูมิ (ระหว่าง 5 ถึง 500 เปอร์เซ็นต์) Write **uint16_t**. |
| virtual void [set_Perspective](./set_perspective/)(**uint8_t**) | ตั้งค่าเปอร์เซ็นต์มุมมอง (field of view angle) สำหรับแผนภูมิ 3D (ระหว่าง 0 ถึง 100) จะถูกละเว้นหากค่า RightAngleAxes เป็น true Write **uint8_t**. |
| virtual void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) | กำหนดว่าแกนของแผนภูมิอยู่ในมุมฉากหรือไม่ แทนที่จะวาดในมุมมองเชิงลึก Write **bool**. |
| virtual void [set_RotationX](./set_rotationx/)(**int8_t**) | ตั้งค่ามุมการหมุนรอบแกน X (คือในทิศทาง Y สำหรับแผนภูมิ 3D) (ระหว่าง -90 ถึง 90 องศา) Write **int8_t**. |
| virtual void [set_RotationY](./set_rotationy/)(**uint16_t**) | ตั้งค่ามุมการหมุนรอบแกน Y (คือในทิศทาง X สำหรับแผนภูมิ 3D) (ระหว่าง 0 ถึง 360 องศา) Write **uint16_t**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็น weak pointer (แทนที่ shared) ทำให้สามารถสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak ได้. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; ให้ใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog of C# [Object.ToString()](../../system/object/tostring/) method. Enables converting custom objects to string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implements C# typeof([System.Object](../../system/object/)) construct. |
| void [Unlock](../../system/object/unlock/)() | Implements C# lock() statement unlocking. Call directly or use [LockContext](../../system/lockcontext/) sentry object. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Increments weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrements weak reference count. Shouldn't be called directly; instead, use smart pointers or ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ คืนค่าโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [Object](../../system/object/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)