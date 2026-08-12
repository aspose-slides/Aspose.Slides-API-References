---
title: BoxedValueBase
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: "คลาสฐานที่กำหนดอินเทอร์เฟซและติดตั้งเมธอดพื้นฐานบางส่วนของคลาสลูกที่แทนค่าที่บรรจุไว้. อ็อบเจกต์ของคลาสนี้ควรสร้างด้วยฟังก์ชัน System::MakeObject() เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อขัดแย้ง. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ System::SmartPtr แล้วใช้พอยน์เตอร์นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์."
type: docs
weight: 131
url: /th/system/boxedvaluebase/
---
## BoxedValueBase คลาส

คลาสฐานที่กำหนดอินเทอร์เฟซและทำการติดตั้งเมธอดพื้นฐานบางส่วนของคลาสสืบทอดที่แทนค่าที่บรรจุไว้. อ็อบเจกต์ของคลาสนี้ควรสร้างด้วยฟังก์ชัน [System::MakeObject()](../makeobject/) เท่านั้น. อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new, เพราะจะทำให้เกิดข้อผิดพลาดขณะรันไทม์และ/หรือข้อขัดแย้ง. ควรห่อคลาสนี้ด้วยพอยน์เตอร์ [System::SmartPtr](../smartptr/) แล้วใช้พอยน์เตอร์นี้เพื่อส่งผ่านไปยังฟังก์ชันเป็นอาร์กิวเมนต์.

```cpp
class BoxedValueBase : public virtual System::Object
```

## เมธอด

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | เปรียบเทียบอ็อบเจกต์โดยใช้ semantics ของ C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบอ็อบเจกต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ซึ่ง NaN สองค่าจะถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจุดลอยตามสไตล์ C# ซึ่ง NaN สองค่าจะถือว่าเท่ากัน แม้ว่าตาม IEC 60559:1989 NaN ไม่เท่ากับค่าใดๆ รวมถึง NaN เอง. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | สำหรับการใช้งานภายในเท่านั้น. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | รับโครงสร้างข้อมูลตัวนับอ้างอิงที่เชื่อมโยงกับอ็อบเจกต์. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | เป็นฟังก์ชันที่คล้ายกับเมธอด C# [Object.GetHashCode()](../object/gethashcode/). เปิดใช้งานการทำแฮชของอ็อบเจกต์แบบกำหนดเอง. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | รับประเภทจริงของอ็อบเจกต์. เป็นฟังก์ชันที่คล้ายกับการเรียก C# [System.Object.GetType()](../object/gettype/). |
| virtual [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | ส่งคืนค่าที่แสดงประเภทของค่าที่บรรจุโดยอ็อบเจกต์ปัจจุบัน. |
| virtual **uint64_t** [GetUnsignedLongLongValue](./getunsignedlonglongvalue/)() const | แปลงค่าที่บรรจุโดยอ็อบเจกต์ปัจจุบันเป็นค่าตัวเลขเต็ม 64 บิต. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | ตรวจสอบว่าอ็อบเจกต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType. เป็นฟังก์ชันที่คล้ายกับโอเปอเรเตอร์ 'is' ของ C#. |
| virtual **bool** [IsBoxedEnum](./isboxedenum/)() | กำหนดว่าอ็อบเจกต์ปัจจุบันเป็นค่าที่บรรจุของประเภท enum หรือไม่. |
| void [Lock](../object/lock/)() | ทำหน้าที่ล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้ [LockContext](../lockcontext/) วัตถุ sentinel. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | เป็นฟังก์ชันที่คล้ายกับเมธอด C# [Object.MemberwiseClone()](../object/memberwiseclone/). เปิดใช้งานการทำสำเนาของประเภทที่กำหนดเอง. |
| [Object](../object/object/)() | สร้างอ็อบเจกต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
| [Object](../object/object/)([Object](../object/) const\&) | คอนสตรัคเตอร์สำเนา. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | โอเปอร์เรเตอร์กำหนดค่า. จริงๆ แล้วไม่ได้คัดลอกอะไรเลย เพียงแค่เริ่มต้นอ็อบเจกต์ใหม่และเปิดใช้งานการคัดลอกสร้างซับคลาส. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | บรรจุค่าคงที่ของ enumeration ที่ระบุด้วยชื่อที่ระบุ พารามิเตอร์ระบุว่าควรละเว้นตัวอักษรใหญ่/เล็กเมื่อแปลความสตริงที่ระบุชื่อของค่าคงที่ enumeration. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&) | บรรจุค่าคงที่ของ enumeration ที่ระบุด้วยชื่อที่ระบุ. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบอ็อบเจกต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ็อบเจกต์ประเภทค่าโดยอ้างอิงกับ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | การเฉพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | การเฉพาะของ [Object::ReferenceEquals](../object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | ลดจำนวนตัวนับอ้างอิงที่แชร์ลงตามค่าที่ระบุ. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าอาร์กิวเมนต์เท็มเพลตที่ n ให้เป็น weak pointer (แทนที่จะแชร์) และอนุญาตให้เปลี่ยนพอยน์เตอร์ในคอนเทนเนอร์เป็นโหมด weak. |
| int [SharedCount](../object/sharedcount/)() const | รับค่าปัจจุบันของตัวนับอ้างอิงที่แชร์. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | ลดจำนวนและคืนค่าตัวนับอ้างอิงที่แชร์. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| [System::String](../string/) [ToString](./tostring/)(const [System::String](../string/)\&) const | แปลงอ็อบเจกต์ที่บรรจุเป็นสตริงโดยใช้รูปแบบสตริงที่ระบุ. |
| virtual [String](../string/) [ToString](./tostring/)() const | เป็นฟังก์ชันที่คล้ายกับเมธอด C# [Object.ToString()](../object/tostring/). เปิดใช้งานการแปลงอ็อบเจกต์แบบกำหนดเองเป็นสตริง. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | ทำหน้าที่สร้างโครงสร้าง typeof([System.Object](../object/)) ของ C#. |
| void [Unlock](../object/unlock/)() | ทำหน้าที่ปลดล็อกตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้ [LockContext](../lockcontext/) วัตถุ sentinel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | เพิ่มจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | ลดจำนวนตัวนับอ้างอิงแบบ weak. ไม่ควรเรียกโดยตรง; แทนที่ควรใช้ smart pointers หรือ ThisProtector. |
| virtual  [~Object](../object/~object/)() | ทำลายอ็อบเจกต์. ปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |

## ดูเพิ่มเติม

* คลาส [Object](../object/)
* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)