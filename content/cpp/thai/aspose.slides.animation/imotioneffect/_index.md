---
title: IMotionEffect
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: แสดงพฤติกรรมของเอฟเฟ็กต์การเคลื่อนที่.
type: docs
weight: 287
url: /th/aspose.slides.animation/imotioneffect/
---
## IMotionEffect คลาส

Represent motion effect behavior of effect.

```cpp
class IMotionEffect : public virtual Aspose::Slides::Animation::IBehavior
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้แนวคิดของ C# [Object.Equals](../../system/object/equals/) |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทอ้างอิงในสไตล์ C# |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่าในสไตล์ C# |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมสไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบตัวเลขทศนิยมสไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าตัวใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual [NullableBool](../../aspose.slides/nullablebool/) [get_Accumulate](../ibehavior/get_accumulate/)() | ระบุว่า พฤติกรรมแอนิเมชันถูกสะสมหรือไม่ อ่าน [NullableBool](../../aspose.slides/nullablebool/) |
| virtual [BehaviorAdditiveType](../behavioradditivetype/) [get_Additive](../ibehavior/get_additive/)() | ระบุว่าพฤติกรรมแอนิเมชันปัจจุบันถูกรวมกับแอนิเมชันที่กำลังทำงานอื่น ๆ หรือไม่ อ่าน [BehaviorAdditiveType](../behavioradditivetype/) |
| virtual **float** [get_Angle](./get_angle/)() | อธิบายมุมสัมพัทธ์ของเส้นทางการเคลื่อนที่ อ่าน **float** |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_By](./get_by/)() | อธิบายค่าการออฟเซ็ตสัมพัทธ์สำหรับแอนิเมชัน (เป็นเปอร์เซ็นต์) อ่าน [System::Drawing::PointF](../../system.drawing/pointf/) |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_From](./get_from/)() | ระบุพิกัด x/y ที่เริ่มต้นแอนิเมชันจาก (เป็นเปอร์เซ็นต์) อ่าน [System::Drawing::PointF](../../system.drawing/pointf/) |
| virtual [MotionOriginType](../motionorigintype/) [get_Origin](./get_origin/)() | ระบุจุดกำเนิดของเส้นทางการเคลื่อนที่สัมพันธ์กับสิ่งเช่น การจัดวางของสไลด์ หรือพาเรนท์ อ่าน [MotionOriginType](../motionorigintype/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\> [get_Path](./get_path/)() | ระบุรูปทรงพื้นฐานของเส้นทางตามด้วยพิกัดสำหรับการเคลื่อนที่ของแอนิเมชัน อ่าน [IMotionPath](../imotionpath/) |
| virtual [MotionPathEditMode](../motionpatheditmode/) [get_PathEditMode](./get_patheditmode/)() | ระบุว่าเส้นทางการเคลื่อนที่ทำอย่างไรเมื่อรูปร่างถูกย้าย อ่าน [MotionPathEditMode](../motionpatheditmode/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorPropertyCollection](../ibehaviorpropertycollection/)\> [get_Properties](../ibehavior/get_properties/)() | แสดงคุณสมบัติของพฤติกรรม อ่านอย่างเดียว [IBehaviorPropertyCollection](../ibehaviorpropertycollection/) |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_RotationCenter](./get_rotationcenter/)() | อธิบายจุดศูนย์กลางของการหมุนที่ใช้หมุนเส้นทางการเคลื่อนที่ตามมุม X อ่าน [System::Drawing::PointF](../../system.drawing/pointf/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](../ibehavior/get_timing/)() | แสดงคุณสมบัติเวลา สำหรับพฤติกรรมเอฟเฟกต์ อ่าน [ITiming](../itiming/) |
| virtual [System::Drawing::PointF](../../system.drawing/pointf/) [get_To](./get_to/)() | ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟกต์การเคลื่อนที่ของแอนิเมชัน (เป็นเปอร์เซ็นต์) อ่าน [System::Drawing::PointF](../../system.drawing/pointf/) |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เทียบเท่ากับเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/) ทำให้สามารถแฮชอ็อบเจ็กต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์ เทียบเท่าการเรียก C# [System.Object.GetType()](../../system/object/gettype/) |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของชนิดที่อธิบายโดย targetType เทียบเท่ากับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เทียบเท่ากับเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) ทำให้สามารถทำสำเนา (clone) ชนิดที่กำหนดเองได้ |
|  [Object](../../system/object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรัคเตอร์คัดลอก ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และทำให้สามารถคัดลอกสร้างซับคลาสได้ |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | ตัวดำเนินการมอบหมาย ไม่ได้คัดลอกอะไรจริง ๆ เพียงเริ่มต้นอ็อบเจ็กต์ใหม่และทำให้สามารถคัดลอกสร้างซับคลาสได้ |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ประเภทค่ากับ nullptr โดยอ้างอิง |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | รูปแบบเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | รูปแบบเฉพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [set_Accumulate](../ibehavior/set_accumulate/)([NullableBool](../../aspose.slides/nullablebool/)) | ระบุว่า พฤติกรรมแอนิเมชันถูกสะสมหรือไม่ เขียน [NullableBool](../../aspose.slides/nullablebool/) |
| virtual void [set_Additive](../ibehavior/set_additive/)([BehaviorAdditiveType](../behavioradditivetype/)) | ระบุว่าพฤติกรรมแอนิเมชันปัจจุบันถูกรวมกับแอนิเมชันที่กำลังทำงานอื่น ๆ หรือไม่ เขียน [BehaviorAdditiveType](../behavioradditivetype/) |
| virtual void [set_Angle](./set_angle/)(**float**) | อธิบายมุมสัมพัทธ์ของเส้นทางการเคลื่อนที่ เขียน **float** |
| virtual void [set_By](./set_by/)([System::Drawing::PointF](../../system.drawing/pointf/)) | อธิบายค่าการออฟเซ็ตสัมพัทธ์สำหรับแอนิเมชัน (เป็นเปอร์เซ็นต์) เขียน [System::Drawing::PointF](../../system.drawing/pointf/) |
| virtual void [set_From](./set_from/)([System::Drawing::PointF](../../system.drawing/pointf/)) | ระบุพิกัด x/y ที่เริ่มต้นแอนิเมชันจาก (เป็นเปอร์เซ็นต์) เขียน [System::Drawing::PointF](../../system.drawing/pointf/) |
| virtual void [set_Origin](./set_origin/)([MotionOriginType](../motionorigintype/)) | ระบุจุดกำเนิดของเส้นทางการเคลื่อนที่สัมพันธ์กับสิ่งเช่น การจัดวางของสไลด์ หรือพาเรนท์ เขียน [MotionOriginType](../motionorigintype/) |
| virtual void [set_Path](./set_path/)([System::SharedPtr](../../system/sharedptr/)\<[IMotionPath](../imotionpath/)\>) | ระบุรูปทรงพื้นฐานของเส้นทางตามด้วยพิกัดสำหรับการเคลื่อนที่ของแอนิเมชัน เขียน [IMotionPath](../imotionpath/) |
| virtual void [set_PathEditMode](./set_patheditmode/)([MotionPathEditMode](../motionpatheditmode/)) | ระบุว่าเส้นทางการเคลื่อนที่ทำอย่างไรเมื่อรูปร่างถูกย้าย เขียน [MotionPathEditMode](../motionpatheditmode/) |
| virtual void [set_RotationCenter](./set_rotationcenter/)([System::Drawing::PointF](../../system.drawing/pointf/)) | อธิบายจุดศูนย์กลางของการหมุนที่ใช้หมุนเส้นทางการเคลื่อนที่ตามมุม X เขียน [System::Drawing::PointF](../../system.drawing/pointf/) |
| virtual void [set_Timing](../ibehavior/set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | แสดงคุณสมบัติเวลา สำหรับพฤติกรรมเอฟเฟกต์ เขียน [ITiming](../itiming/) |
| virtual void [set_To](./set_to/)([System::Drawing::PointF](../../system.drawing/pointf/)) | ระบุตำแหน่งเป้าหมายสำหรับเอฟเฟกต์การเคลื่อนที่ของแอนิเมชัน (เป็นเปอร์เซ็นต์) เขียน [System::Drawing::PointF](../../system.drawing/pointf/) |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งอาร์กิวเมนต์เทมเพลตที่ n ให้เป็น weak pointer (แทน shared) อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์ ควรไม่เรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนตัวนับอ้างอิงที่แชร์และคืนค่า ควรไม่เรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เทียบเท่ากับเมธอด C# [Object.ToString()](../../system/object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C# |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อกตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนตัวนับ weak reference. ควรไม่เรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนตัวนับ weak reference. ควรไม่เรียกโดยตรง; ให้ใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน |
| virtual  [~Object](../../system/object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |
## ดูเพิ่มเติม

* คลาส [IBehavior](../ibehavior/)
* เนมสเปซ [Aspose::Slides::Animation](../)
* ไลบรารี [Aspose.Slides](../../)