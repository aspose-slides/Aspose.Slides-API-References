---
title: MotionEffect
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: เป็นตัวแทนพฤติกรรมของเอฟเฟ็กต์การเคลื่อนที่
type: docs
weight: 469
url: /th/aspose.slides.animation/motioneffect/
---
## MotionEffect คลาส

อธิบายพฤติกรรมผลกระทบการเคลื่อนที่ของเอฟเฟ็กต์

```cpp
class MotionEffect : public Aspose::Slides::Animation::Behavior,
                     public Aspose::Slides::Animation::IMotionEffect
```

## วิธีการ

| วิธีการ | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบวัตถุโดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบวัตถุประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | เลียนแบบการเปรียบเทียบจุดลอยแบบ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 ค่า NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | เลียนแบบการเปรียบเทียบจุดลอยแบบ C# ที่สองค่า NaN ถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 ค่า NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../behavior/get_accumulate/)() override | ระบุว่า พฤติกรรมการเคลื่อนไหวถูกสะสมหรือไม่ อ่าน [NullableBool](../../aspose.slides/nullablebool/). |
| [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../behavior/get_additive/)() override | ระบุว่าพฤติกรรมการเคลื่อนไหวปัจจุบันถูกรวมกับการเคลื่อนไหวที่กำลังทำงานอื่นหรือไม่ อ่าน [BehaviorAdditiveType](../behavioradditivetype/). |
| **float** [get_Angle](./get_angle/)() override | อธิบายมุมสัมพัทธ์ของเส้นทางการเคลื่อนไหว อ่าน **float**. |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() override | อธิบายค่าการเยื้องสัมพัทธ์สำหรับการเคลื่อนไหว (เป็นเปอร์เซ็นต์) อ่าน [System::Drawing::PointF](../../system.drawing/pointf/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() override | ระบุตำแหน่งพิกัด x/y เพื่อเริ่มการเคลื่อนไหว (เป็นเปอร์เซ็นต์) อ่าน [System::Drawing::PointF](../../system.drawing/pointf/). |
| [MotionOriginType](../motionorigintype/) [get_Origin](./get_origin/)() override | ระบุว่า จุดเริ่มต้นของเส้นทางการเคลื่อนไหวสัมพันธ์กับอะไร เช่น การจัดวางสไลด์ หรือพาเรนท์ อ่าน [MotionOriginType](../motionorigintype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\> [get_Path](./get_path/)() override | ระบุพรินมิติของเส้นทางที่ตามด้วยพิกัดสำหรับการเคลื่อนไหวของแอนิเมชัน อ่าน [IMotionPath](../imotionpath/). |
| [MotionPathEditMode](../motionpatheditmode/) [get_PathEditMode](./get_patheditmode/)() override | ระบุว่าทางการเคลื่อนที่เปลี่ยนแปลงอย่างไรเมื่อรูปร่างถูกย้าย อ่าน [MotionPathEditMode](../motionpatheditmode/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../behavior/get_properties/)() override | แสดงคุณสมบัติของพฤติกรรม อ่านอย่างเดียว [IBehaviorPropertyCollection](../ibehaviorpropertycollection/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_RotationCenter](./get_rotationcenter/)() override | อธิบายจุดศูนย์กลางของการหมุนที่ใช้เพื่อหมุนเส้นทางการเคลื่อนไหวตามมุม X อ่าน [System::Drawing::PointF](../../system.drawing/pointf/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../behavior/get_timing/)() override | แสดงคุณสมบัติการจับเวลาสำหรับพฤติกรรมเอฟเฟ็กต์ อ่าน [ITiming](../itiming/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() override | ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟ็กต์การเคลื่อนไหวของแอนิเมชัน (เป็นเปอร์เซ็นต์) อ่าน [System::Drawing::PointF](../../system.drawing/pointf/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลเคาน์เตอร์อ้างอิงที่เชื่อมโยงกับวัตถุ. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแบบจำลองของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). เปิดใช้งานการแฮชของวัตถัสามกำหนด. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของวัตถุ. เป็นแบบจำลองของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าวัตถุเป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นแบบจำลองของตัวดำเนินการ 'is' ของ C#. |
| void [Lock](../../system/object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) สังเกตการณ์. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบจำลองของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). เปิดใช้งานการคัดลอกของชนิดที่กำหนดเอง. |
|  [MotionEffect](./motioneffect/)() |  |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์สำเนา. จริงๆ แล้วไม่คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย. จริงๆ แล้วไม่คัดลอกอะไรเลย เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบวัตถุโดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของวัตถุประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนเคาน์เตอร์อ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| void [set_Accumulate](../behavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) override | ระบุว่า พฤติกรรมการเคลื่อนไหวถูกสะสมหรือไม่ เขียน [NullableBool](../../aspose.slides/nullablebool/). |
| void [set_Additive](../behavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) override | ระบุว่าพฤติกรรมการเคลื่อนไหวปัจจุบันถูกรวมกับการเคลื่อนไหวที่กำลังทำงานอื่นหรือไม่ เขียน [BehaviorAdditiveType](../behavioradditivetype/). |
| void [set_Angle](./set_angle/)(**float**) override | อธิบายมุมสัมพัทธ์ของเส้นทางการเคลื่อนไหว เขียน **float**. |
| void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | อธิบายค่าการเยื้องสัมพัทธ์สำหรับการเคลื่อนไหว (เป็นเปอร์เซ็นต์) เขียน [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | ระบุตำแหน่งพิกัด x/y เพื่อเริ่มการเคลื่อนไหว (เป็นเปอร์เซ็นต์) เขียน [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_Origin](./set_origin/)([MotionOriginType](../motionorigintype/)) override | ระบุว่าจุดเริ่มต้นของเส้นทางการเคลื่อนไหวสัมพันธ์กับอะไร เช่น การจัดวางสไลด์ หรือพาเรนท์ เขียน [MotionOriginType](../motionorigintype/). |
| void [set_Path](./set_path/)([System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\>) override | ระบุพรินมิติของเส้นทางที่ตามด้วยพิกัดสำหรับการเคลื่อนไหวของแอนิเมชัน เขียน [IMotionPath](../imotionpath/). |
| void [set_PathEditMode](./set_patheditmode/)([MotionPathEditMode](../motionpatheditmode/)) override | ระบุว่าทางการเคลื่อนที่เปลี่ยนแปลงอย่างไรเมื่อรูปร่างถูกย้าย เขียน [MotionPathEditMode](../motionpatheditmode/). |
| void [set_RotationCenter](./set_rotationcenter/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | อธิบายจุดศูนย์กลางของการหมุนที่ใช้เพื่อหมุนเส้นทางการเคลื่อนไหวตามมุม X เขียน [System::Drawing::PointF](../../system.drawing/pointf/). |
| void [set_Timing](../behavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) override | แสดงคุณสมบัติการจับเวลาสำหรับพฤติกรรมเอฟเฟ็กต์ เขียน [ITiming](../itiming/). |
| void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) override | ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟ็กต์การเคลื่อนไหวนแอนิเมชัน (เป็นเปอร์เซ็นต์) เขียน [System::Drawing::PointF](../../system.drawing/pointf/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | กำหนดอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทนที่จะเป็น shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของเคาน์เตอร์อ้างอิงที่แชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มเคาน์เตอร์อ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดและคืนค่าเคาน์เตอร์อ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแบบจำลองของเมธอด C# [Object.ToString()](../../system/object/tostring/). เปิดใช้งานการแปลงวัตถุที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ทำหน้าที่ตาม construct typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ [LockContext](../../system/lockcontext/) สังเกตการณ์. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มเคาน์เตอร์อ้างอิงแบบ weak ควรไม่เรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดเคาน์เตอร์อ้างอิงแบบ weak ควรไม่เรียกโดยตรง; แทนใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Behavior](../behavior/)
* คลาส [IMotionEffect](../imotioneffect/)
* เนมสเปซ [Aspose::Slides::Animation](../)
* ไลบรารี [Aspose.Slides](../../)