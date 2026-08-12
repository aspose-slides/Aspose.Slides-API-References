---
title: Rotation3D
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงการหมุน 3D ของแผนภูมิ
type: docs
weight: 1327
url: /th/aspose.slides.charts/rotation3d/
---
## Rotation3D คลาส


แทนการหมุน 3D ของแผนภูมิ.

```cpp
class Rotation3D : public Aspose::Slides::Charts::IRotation3D,
                   public Aspose::Slides::IDOMObject
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้การทำงานของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่ NaN สองค่าถูกถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| **uint16_t** [get_DepthPercents](./get_depthpercents/)() override | คืนค่าความลึกของแผนภูมิ 3D ในรูปแบบเปอร์เซ็นต์ของความกว้างของแผนภูมิ (ระหว่าง 20 ถึง 2000 เปอร์เซ็นต์) อ่าน **uint16_t** |
| **uint16_t** [get_HeightPercents](./get_heightpercents/)() override | กำหนดความสูงของแผนภูมิ 3D ในรูปแบบเปอร์เซ็นต์ของความกว้างของแผนภูมิ (ระหว่าง 5 ถึง 500 เปอร์เซ็นต์) อ่าน **uint16_t** |
| **uint8_t** [get_Perspective](./get_perspective/)() override | คืนค่ามุมมอง (มุมมองของฟิลด์) สำหรับแผนภูมิ 3D (ระหว่าง 0 ถึง 240) จะละเว้นหากค่า property RightAngleAxes เป็น true อ่าน **uint8_t** |
| **bool** [get_RightAngleAxes](./get_rightangleaxes/)() override | กำหนดว่ากราฟแกนตั้งฉากกันหรือไม่ แทนที่จะวาดในมุมมองเชิงมุม กล่าวคือกำหนดว่ามุมของแกนกราฟเป็นอิสระจากการหมุนหรือการยกของกราฟหรือไม่ อ่าน **bool** |
| **int8_t** [get_RotationX](./get_rotationx/)() override | คืนค่ามุมการหมุนรอบแกน X (หรือทิศทาง Y สำหรับแผนภูมิ 3D) (ระหว่าง -90 ถึง 90 องศา) property นี้สอดคล้องกับรายการ rotX (การหมุน X) 21.2.2.157 ใน ECMA-376 และกับตัวเลือก "Y Rotation" ใน PowerPoint 2007+ อ่าน **int8_t** |
| **uint16_t** [get_RotationY](./get_rotationy/)() override | คืนค่ามุมการหมุนรอบแกน Y (หรือทิศทาง X สำหรับแผนภูมิ 3D) (ระหว่าง 0 ถึง 360 องศา) property นี้สอดคล้องกับรายการ rotY (การหมุน Y) 21.2.2.158 ใน ECMA-376 และกับตัวเลือก "X Rotation" ใน PowerPoint 2007+ อ่าน **uint16_t** |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับการอ้างอิงที่เชื่อมโยงกับวัตถุ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของวัตถุที่กำหนดเอง |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ คล้ายกับการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ คล้ายกับโอเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคัดลอกประเภทที่กำหนดเอง |
|  [Object](../../system/object/object/)() | สร้างวัตถุและเริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | ตัวสร้างสำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกในการสร้างคลาสลูก |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นวัตถุใหม่และเปิดใช้งานการคัดลอกในการสร้างคลาสลูก |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบออบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การกำหนดพิเศษของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงร่วมลงตามค่าที่ระบุ |
| void [set_DepthPercents](./set_depthpercents/)(**uint16_t**) override | กำหนดความลึกของแผนภูมิ 3D ในรูปแบบเปอร์เซ็นต์ของความกว้างของแผนภูมิ (ระหว่าง 20 ถึง 2000 เปอร์เซ็นต์) เขียน **uint16_t** |
| void [set_HeightPercents](./set_heightpercents/)(**uint16_t**) override | กำหนดความสูงของแผนภูมิ 3D ในรูปแบบเปอร์เซ็นต์ของความกว้างของแผนภูมิ (ระหว่าง 5 ถึง 500 เปอร์เซ็นต์) เขียน **uint16_t** |
| void [set_Perspective](./set_perspective/)(**uint8_t**) override | กำหนดค่าสมมุติ (มุมมองของฟิลด์) สำหรับแผนภูมิ 3D (ระหว่าง 0 ถึง 240) จะละเว้นหากค่า property RightAngleAxes เป็น true เขียน **uint8_t** |
| void [set_RightAngleAxes](./set_rightangleaxes/)(**bool**) override | กำหนดว่ากราฟแกนตั้งฉากกันหรือไม่ แทนที่จะวาดในมุมมองเชิงมุม กล่าวคือกำหนดว่ามุมของแกนกราฟเป็นอิสระจากการหมุนหรือการยกของกราฟหรือไม่ เขียน **bool** |
| void [set_RotationX](./set_rotationx/)(**int8_t**) override | กำหนดมุมการหมุนรอบแกน X (หรือทิศทาง Y สำหรับแผนภูมิ 3D) (ระหว่าง -90 ถึง 90 องศา) property นี้สอดคล้องกับรายการ rotX (การหมุน X) 21.2.2.157 ใน ECMA-376 และกับตัวเลือก "Y Rotation" ใน PowerPoint 2007+ เขียน **int8_t** |
| void [set_RotationY](./set_rotationy/)(**uint16_t**) override | กำหนดมุมการหมุนรอบแกน Y (หรือทิศทาง X สำหรับแผนภูมิ 3D) (ระหว่าง 0 ถึง 360 องศา) property นี้สอดคล้องกับรายการ rotY (การหมุน Y) 21.2.2.158 ใน ECMA-376 และกับตัวเลือก "X Rotation" ใน PowerPoint 2007+ เขียน **uint16_t** |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าตัวอาร์กิวเมนต์เทมเพลตที่ n เป็น weak pointer (แทนที่ shared) ทำให้สามารถสลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak ได้ |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงร่วม |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มตัวนับการอ้างอิงร่วม ควรไม่เรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับการอ้างอิงร่วม ควรไม่เรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุที่กำหนดเองเป็นสตริง |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มตัวนับการอ้างอิง weak ควรไม่เรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดตัวนับการอ้างอิง weak ควรไม่เรียกโดยตรง; ใช้ smart pointers หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายวัตถุและปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [IRotation3D](../irotation3d/)
* คลาส [IDOMObject](../../aspose.slides/idomobject/)
* เนมสเปซ [Aspose::Slides::Charts](../)
* ไลบรารี [Aspose.Slides](../../)