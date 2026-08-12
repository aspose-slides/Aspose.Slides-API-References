---
title: ICloneable
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "กำหนดเมธอดที่ทำให้สามารถโคลนอ็อบเจกต์ได้ - การสร้างสำเนาของอ็อบเจกต์. อ็อบเจกต์ของคลาสนี้ควรจะถูกจัดสรรเท่านั้นโดยใช้ฟังก์ชัน System::MakeObject() . อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแต็กหรือโดยใช้โอเปอเรเตอร์ new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 911
url: /th/system/icloneable/
---
## ICloneable คลาส

กำหนดเมธอดที่ทำให้สามารถโคลนอ็อบเจกต์ได้ - การสร้างสำเนาของอ็อบเจกต์. อ็อบเจกต์ของคลาสนี้ควรจะถูกจัดสรรเท่านั้นโดยใช้ฟังก์ชัน [System::MakeObject()](../makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแต็กหรือโดยใช้โอเปอเรเตอร์ new เนื่องจากจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อผิดพลาดการอ้างอิง. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../smartptr/) เสมอและใช้พอยน์เตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class ICloneable : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\> [Clone](./clone/)() | สร้างสำเนาของอ็อบเจกต์ปัจจุบันและคืนพอยน์เตอร์แบบ shared ให้กับมัน. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้เซมานติกของ C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ของ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ของ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่สองค่า NaN จะถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 ค่า NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยแบบ C# ที่สองค่า NaN จะถือว่าเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 ค่า NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | ใช้เพื่อวัตถุประสงค์ภายในเท่านั้น. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | เป็นอนุกรมของเมธอด C# [Object.GetHashCode()](../object/gethashcode/). ทำให้สามารถทำแฮชอ็อบเจกต์แบบกำหนดเองได้. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นอนุกรมของการเรียก C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นอนุกรมของโอเปอเรเตอร์ 'is' ของ C#. |
| void [Lock](../object/lock/)() | ทำหน้าที่เป็นการล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | เป็นอนุกรมของเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). ทำให้สามารถโคลนประเภทกำหนดเองได้. |
|  [Object](../object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์สำเนา. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย, เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และทำให้สามารถคอนสตรัคต์สำเนาสำหรับซับคลาสได้. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ แล้วไม่ได้คัดลอกอะไรเลย, เพียงเริ่มต้นอ็อบเจกต์ใหม่และทำให้สามารถคอนสตรัคต์สำเนาสำหรับซับคลาสได้. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบการอ้างอิงของอ็อบเจกต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การจำแนกพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การจำแนกพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแบบ shared ลงตามค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n ให้เป็นพอยน์เตอร์แบบ weak (แทนที่จะแบ่งปันแบบ shared). อนุญาตให้สลับพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับการอ้างอิงแบบ shared. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ shared. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงแบบ shared แล้วคืนค่า. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | เป็นอนุกรมของเมธอด C# [Object.ToString()](../object/tostring/). ทำให้สามารถแปลงอ็อบเจกต์กำหนดเองเป็นสตริงได้. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ทำหน้าที่เป็นโครงสร้าง C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | ทำหน้าที่เป็นการปลดล็อกของคำสั่ง C# lock(). เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; ควรใช้สมาร์ทพอยน์เตอร์หรือ ThisProtector แทน. |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจกต์. ปลอดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ดูเพิ่มเติม

* คลาส [Object](../object/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)