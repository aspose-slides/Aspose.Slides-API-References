---
title: ICustomFormatter
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: "กำหนดเมธอดที่ทำการฟอร์แมตสตริงของค่าที่แทนโดยอ็อบเจ็กต์ที่ระบุไว้เฉพาะ อ็อบเจ็กต์ของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน System::MakeObject() เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เพราะจะทำให้เกิดข้อผิดพลาดระหว่างรันไทม์และ/หรือการตรวจสอบล้มเหลว เสมอห่อคลาสนี้ด้วย pointer System::SmartPtr และใช้ pointer นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 950
url: /th/system/icustomformatter/
---
## ICustomFormatter คลาส

กำหนดเมธอดที่ทำการฟอร์แมตสตริงของค่าที่แทนโดยอ็อบเจ็กต์ที่ระบุไว้ อ็อบเจ็กต์ของคลาสนี้ควรกำหนดหน่วยความจำโดยใช้ฟังก์ชัน [System::MakeObject()](../makeobject/) เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ตัวดำเนินการ new เนื่องจากจะทำให้เกิดข้อผิดพลาดเวลาเรียกใช้และ/หรือการตรวจสอบล้มเหลว เสมอห่อคลาสนี้เข้าสู่ pointer [System::SmartPtr](../smartptr/) และใช้ pointer นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
class ICustomFormatter : public virtual System::Object
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้รูปแบบการทำงานของ C# [Object.Equals](../object/equals/) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ชนิดอ้างอิงตามสไตล์ของ C# |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ชนิดค่าในสไตล์ของ C# |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดทศนิยมแบบ C# ที่สองค่า NaN ถือเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ แม้แต่ NaN |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดทศนิยมแบบ C# ที่สองค่า NaN ถือเท่ากันแม้ตามมาตรฐาน IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ แม้แต่ NaN |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| virtual [System::String](../string/) [Format](./format/)([System::String](../string/), [System::SharedPtr](../sharedptr/)\<[System::Object](../object/)\>, [System::SharedPtr](../sharedptr/)\<[System::IFormatProvider](../iformatprovider/)\>) | คืนค่าการแสดงผลเป็นสตริงของค่าที่อ็อบเจ็กต์ปัจจุบันแทนด้วยรูปแบบที่ระบุ |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | คล้ายกับเมธอด C# [Object.GetHashCode()](../object/gethashcode/) ทำให้สามารถทำแฮชของอ็อบเจ็กต์แบบกำหนดเองได้ |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | รับชนิดจริงของอ็อบเจ็กต์ คล้ายกับการเรียก C# [System.Object.GetType()](../object/gettype/) |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType คล้ายกับตัวดำเนินการ 'is' ของ C# |
| void [Lock](../object/lock/)() | ดำเนินการล็อคตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | คล้ายกับเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรเลย จริง ๆ แล้วเพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาสำหรับซับคลาส |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | ตัวดำเนินการกำหนดค่า ไม่ได้คัดลอกอะไรเลย จริง ๆ แล้วเพียงเริ่มต้นอ็อบเจ็กต์ใหม่และเปิดให้สร้างสำเนาสำหรับซับคลาส |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์ตามอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์ตามอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงอ็อบเจ็กต์ชนิดค่ากับ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การพิเศษของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่ใช้ร่วมกันลงตามค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็น weak pointer (แทน shared) ให้สามารถสลับ pointer ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่ใช้ร่วมกัน |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มตัวนับอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดและคืนค่าตัวนับอ้างอิงที่ใช้ร่วมกัน ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual [String](../string/) [ToString](../object/tostring/)() const | คล้ายกับเมธอด C# [Object.ToString()](../object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์แบบกำหนดเองเป็นสตริง |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ดำเนินการสร้าง typeof([System.Object](../object/)) ของ C# |
| void [Unlock](../object/unlock/)() | ดำเนินการปลดล็อคตามคำสั่ง lock() ของ C# เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดตัวนับอ้างอิงแบบ weak ไม่ควรเรียกโดยตรง; ควรใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Object](../object/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)