---
title: RunWorkerCompletedEventArgs
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "อินสแตนซ์ของคลาสนี้จะถูกส่งเป็นอาร์กิวเมนต์ให้กับ delegate RunWorkerCompletedEventHandler. ออบเจ็กต์ของคลาสนี้ควรจะถูกจัดสรรเฉพาะโดยใช้ฟังก์ชัน System::MakeObject(). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแต็คหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือการตรวจสอบความถูกต้อง. ควรห่อหุ้มคลาสนี้ในพอยเตอร์ System::SmartPtr และใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน."
type: docs
weight: 183
url: /th/system.componentmodel/runworkercompletedeventargs/
---
## RunWorkerCompletedEventArgs คลาส


อินสแตนซ์ของคลาสนี้จะถูกส่งเป็นอาร์กิวเมนต์ให้กับ delegate RunWorkerCompletedEventHandler. ออบเจ็กต์ของคลาสนี้ควรจะถูกจัดสรรเฉพาะโดยใช้ฟังก์ชัน [System::MakeObject()](../../system/makeobject/). อย่าสร้างอินสแตนซ์ของประเภทนี้บนสแตกหรือโดยใช้ operator new เพราะจะทำให้เกิดข้อผิดพลาดรันไทม์และ/หรือข้อผิดพลาดการตรวจสอบ. ควรห่อหุ้มคลาสนี้ในพอยเตอร์ [System::SmartPtr](../../system/smartptr/) และใช้พอยเตอร์นี้เพื่อส่งเป็นอาร์กิวเมนต์ให้กับฟังก์ชัน.

```cpp
class RunWorkerCompletedEventArgs : public System::ComponentModel::AsyncCompletedEventArgs
```

## เมธอด

| Method | Description |
| --- | --- |
|  [AsyncCompletedEventArgs](../asynccompletedeventargs/asynccompletedeventargs/)() | คอนสตรัคเตอร์. |
|  [AsyncCompletedEventArgs](../asynccompletedeventargs/asynccompletedeventargs/)(const [System::Exception](../../system/exception/)\&, **bool**, const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&) | สร้างอินสแตนซ์ใหม่ของคลาส [System.ComponentModel.AsyncCompletedEventArgs](../asynccompletedeventargs/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | เปรียบเทียบออบเจ็กต์โดยใช้ความหมายของ C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทอ้างอิงในสไตล์ C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | เปรียบเทียบออบเจ็กต์ประเภทค่าในสไตล์ C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# ซึ่งสองค่า NaN จะถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | จำลองการเปรียบเทียบจำนวนจุดลอยแบบ C# ซึ่งสองค่า NaN จะถือว่าเท่ากันแม้ตาม IEC 60559:1989 NaN จะไม่เท่ากับค่าใด ๆ รวมถึง NaN ด้วย. |
|  [EventArgs](../../system/eventargs/eventargs/)() | คอนสตรัคเตอร์. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | เพื่อการใช้งานภายในเท่านั้น. |
| **bool** [get_Cancelled](../asynccompletedeventargs/get_cancelled/)() const | รับค่าที่บ่งบอกว่าการดำเนินงานแบบอะซิงโครนัสถูกยกเลิกหรือไม่. true หากการดำเนินงานพื้นหลังถูกยกเลิก; มิฉะนั้น false. ค่าเริ่มต้นคือ false. |
| const [System::Exception](../../system/exception/)\& [get_Error](../asynccompletedeventargs/get_error/)() const | รับค่าที่บ่งบอกว่าข้อผิดพลาดใดเกิดขึ้นระหว่างการดำเนินงานแบบอะซิงโครนัส. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Result](./get_result/)() const | รับค่าที่แสดงผลลัพธ์ของการดำเนินงานแบบอะซิงโครนัส. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_UserState](../asynccompletedeventargs/get_userstate/)() const | รับตัวระบุตัวเอกลักษณ์สำหรับงานอะซิงโครนัส. อ้างอิงออบเจ็กต์ที่ระบุตัวงานอะซิงโครนัสอย่างเป็นเอกลักษณ์; มิฉะนั้น, null หากไม่ได้ตั้งค่าใด ๆ. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | รับโครงสร้างข้อมูลของเคาน์เตอร์อ้างอิงที่เชื่อมโยงกับออบเจ็กต์. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | เป็นแบบจำลองของเมธอด C# [Object.GetHashCode()](../../system/object/gethashcode/). รองรับการแฮชออบเจ็กต์ที่กำหนดเอง. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | รับประเภทจริงของออบเจ็กต์. เป็นแบบจำลองของการเรียก C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | ตรวจสอบว่าออบเจ็กต์เป็นอินสแตนซ์ของประเภทที่อธิบายโดย targetType หรือไม่. เป็นแบบจำลองของออพเรเตอร์ C# 'is'. |
| void [Lock](../../system/object/lock/)() | ดำเนินการล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | เป็นแบบจำลองของเมธอด C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). รองรับการทำสำเนาประเภทที่กำหนดเอง. |
|  [Object](../../system/object/object/)() | สร้างออบเจ็กต์. เริ่มต้นโครงสร้างข้อมูลภายในทั้งหมด. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | คอนสตรักเตอร์สำเนา. จริง ๆ ไม่ได้คัดลอกอะไรเลย, เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการสำเนาสร้างซับคลาส. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | โอเปอเรเตอร์การกำหนดค่า. จริง ๆ ไม่ได้คัดลอกอะไรเลย, เพียงเริ่มต้นออบเจ็กต์ใหม่และเปิดใช้งานการสำเนาสร้างซับคลาส. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | เปรียบเทียบออบเจ็กต์โดยอ้างอิง. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | เปรียบเทียบอ้างอิงของออบเจ็กต์ประเภทค่า กับ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริงและ nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | การจำเพาะของ [Object::ReferenceEquals](../../system/object/referenceequals/) สำหรับกรณีของสตริง. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | ลดจำนวนการอ้างอิงแชร์โดยค่าที่ระบุ. |
|  [RunWorkerCompletedEventArgs](./runworkercompletedeventargs/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>\&, const [System::Exception](../../system/exception/)\&, **bool**) | คอนสตรัคเตอร์. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | ตั้งค่าเทมเพลตอาร์กิวเมนต์ที่ n เป็นพอยเตอร์แบบอ่อน (แทนที่จะแชร์). อนุญาตให้สลับพอยเตอร์ในคอนเทนเนอร์เป็นโหมดอ่อน. |
| int [SharedCount](../../system/object/sharedcount/)() const | รับค่าปัจจุบันของเคาน์เตอร์อ้างอิงแชร์. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | เพิ่มจำนวนการอ้างอิงแชร์. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยเตอร์หรือ ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | ลดจำนวนการอ้างอิงแชร์และคืนค่า. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยเตอร์หรือ ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | เป็นแบบจำลองของเมธอด C# [Object.ToString()](../../system/object/tostring/). รองรับการแปลงออบเจ็กต์ที่กำหนดเองเป็นสตริง. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | ดำเนินการสร้าง typeof([System.Object](../../system/object/)) ของ C#. |
| void [Unlock](../../system/object/unlock/)() | ดำเนินการปลดล็อคตามคำสั่ง lock() ของ C#. เรียกโดยตรงหรือใช้วัตถุ sentinel [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | เพิ่มจำนวนการอ้างอิงแบบอ่อน. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยเตอร์หรือ ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | ลดจำนวนการอ้างอิงแบบอ่อน. ไม่ควรเรียกโดยตรง; ให้ใช้สมาร์ทพอยเตอร์หรือ ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | ทำลายออบเจ็กต์. ปลดปล่อยโครงสร้างข้อมูลภายในทั้งหมด. |
## ฟิลด์

| Field | Description |
| --- | --- |
| static [Empty](../../system/eventargs/empty/) | สมาชิก static ที่เป็นตัวแทนของพอยเตอร์แชร์ "ว่างเปล่า" [EventArgs](../../system/eventargs/) (null-pointer). |
## ดูเพิ่มเติม

* คลาส [AsyncCompletedEventArgs](../asynccompletedeventargs/)
* เนมสเปซ [System::ComponentModel](../)
* ไลบรารี [Aspose.Slides](../../)