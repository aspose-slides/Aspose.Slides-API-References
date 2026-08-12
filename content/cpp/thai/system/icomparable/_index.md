---
title: IComparable
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "กำหนดเมธอดที่เปรียบเทียบสองอ็อบเจ็กต์ อ็อบเจ็กต์ของคลาสนี้ควรจัดสรรด้วยฟังก์ชัน System::MakeObject() เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ ให้ห่อคลาสนี้ไว้ในตัวชี้ System::SmartPtr และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน"
type: docs
weight: 924
url: /th/system/icomparable/
---
## IComparable คลาส

กำหนดเมธอดที่เปรียบเทียบสองอ็อบเจ็กต์ อ็อบเจ็กต์ของคลาสนี้ควรสร้างโดยใช้ฟังก์ชัน [System::MakeObject()](../makeobject/) เท่านั้น อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ ควรห่อคลาสนี้ไว้ในตัวชี้ [System::SmartPtr](../smartptr/) และใช้ตัวชี้นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน

```cpp
template<typename T>class IComparable : public virtual System::Object
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทของอ็อบเจ็กต์ที่เปรียบเทียบกับอ็อบเจ็กต์ปัจจุบัน |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| virtual int [CompareTo](./compareto/)(T) | เปรียบเทียบอ็อบเจ็กต์ปัจจุบันกับอ็อบเจ็กต์ที่ระบุ |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจ็กต์โดยใช้ semantics ของ C# [Object.Equals](../object/equals/) |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ชนิดอ้างอิงในรูปแบบ C# |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจ็กต์ชนิดค่ในรูปแบบ C# |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบแบบ floating point สไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบแบบ floating point สไตล์ C# ซึ่ง NaN สองค่าถือว่าเท่ากันแม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจ็กต์ |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | เป็นการทำงานที่คล้ายกับเมธอด C# [Object.GetHashCode()](../object/gethashcode/) ทำให้สามารถทำแฮชอ็อบเจ็กต์ที่กำหนดเองได้ |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | รับประเภทที่แท้จริงของอ็อบเจ็กต์ เป็นการทำงานที่คล้ายกับการเรียก C# [System.Object.GetType()](../object/gettype/) |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่ เป็นการทำงานที่คล้ายกับโอเปอเรเตอร์ 'is' ของ C# |
| void [Lock](../object/lock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อทำการล็อค เรียกใช้โดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | เป็นเมธอดที่คล้ายกับ C# [Object.MemberwiseClone()](../object/memberwiseclone/) ทำให้สามารถโคลนประเภทที่กำหนดเองได้ |
|  [Object](../object/object/)() | สร้างอ็อบเจ็กต์ เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด |
|  [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์สำเนา ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | โอเปอเรเตอร์การกำหนดค่า ไม่ได้คัดลอกอะไรจริง ๆ เพียงแค่เริ่มต้นอ็อบเจ็กต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจ็กต์โดยอ้างอิง |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจ็กต์ชนิดค่าโดยอ้างอิงกับ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์แม่แบบที่ n ให้เป็น weak pointer (แทนที่เป็น shared) อนุญาตให้สลับตัวชี้ในคอนเทนเนอร์เป็นโหมด weak |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์ |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงที่แชร์ ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector |
| virtual [String](../string/) [ToString](../object/tostring/)() const | เป็นเมธอดที่คล้ายกับ C# [Object.ToString()](../object/tostring/) ทำให้สามารถแปลงอ็อบเจ็กต์ที่กำหนดเองเป็นสตริงได้ |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ทำงานตามโครงสร้าง C# typeof([System.Object](../object/)) |
| void [Unlock](../object/unlock/)() | ทำงานตามคำสั่ง lock() ของ C# เพื่อปลดล็อค เรียกใช้โดยตรงหรือใช้วัตถุ sentinel [LockContext](../lockcontext/) |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มจำนวนตัวนับ weak ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดจำนวนตัวนับ weak ไม่ควรเรียกโดยตรง; แทนให้ใช้ smart pointers หรือ ThisProtector |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจ็กต์ ปล่อยโครงสร้างข้อมูลภายในทั้งหมด |

## ดูเพิ่มเติม

* คลาส [Object](../object/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)