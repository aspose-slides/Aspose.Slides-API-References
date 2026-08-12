---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides สำหรับ C++ API Reference
description: "แสดงถึงคอลเลคชันของ delegate. ประเภทนี้ควรจัดสรรบนสแตกและส่งต่อไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง. ห้ามใช้คลาส System::SmartPtr เพื่อจัดการอ็อบเจ็กต์ของประเภทนี้."
type: docs
weight: 1093
url: /th/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> คลาส


แสดงถึงคอลเลคชันของ delegate. ประเภทนี้ควรจัดสรรบนสแตกและส่งต่อไปยังฟังก์ชันโดยค่า หรือโดยการอ้างอิง. ห้ามใช้คลาส [System::SmartPtr](../smartptr/) เพื่อจัดการอ็อบเจ็กต์ของประเภทนี้.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```


### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| ReturnType | ประเภทค่าที่คืนของเอนทิตีที่สามารถเรียกใช้ได้ซึ่งถูกชี้โดยแต่ละ delegate ในคอลเลคชัน |
| ArgumentTypes | รายการอาร์กิวเมนต์ของเอนทิตีที่สามารถเรียกใช้ได้ซึ่งถูกชี้โดยแต่ละ delegate ในคอลเลคชัน |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | NOT IMPLEMENTED. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | เพิ่ม delegate ที่ระบุลงในคอลเลคชัน |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | เพิ่มอ็อบเจ็กต์ฟังก์ชันที่ระบุลงในคอลเลคชัน delegate. อ็อบเจ็กต์ฟังก์ชันจะถูกแปลงเป็นประเภท delegate Callback ก่อนเพิ่มลงในคอลเลคชัน |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | เพิ่มอ็อบเจ็กต์ MulticastDelegate ที่ระบุลงในคอลเลคชัน delegate |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | เพิ่มเมธอดที่ไม่ใช่สตาติกของอ็อบเจ็กต์ที่ระบุลงในคอลเลคชัน delegate |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | เพิ่มเมธอดที่ไม่ใช่สตาติกของอ็อบเจ็กต์ที่ระบุลงในคอลเลคชัน delegate |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | ลบ delegate ที่ระบุออกจากคอลเลคชัน delegate |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | ลบเมธอดที่ไม่ใช่สตาติกของอ็อบเจ็กต์ที่ระบุออกจากคอลเลคชัน delegate |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | ลบเมธอดที่ไม่ใช่สตาติกของอ็อบเจ็กต์ที่ระบุออกจากคอลเลคชัน delegate |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | ลบอ็อบเจ็กต์ MulticastDelegate ที่ระบุออกจากคอลเลคชัน delegate |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | ลบ delegate ทั้งหมดออกจากคอลเลคชัน delegate |
| **bool** [empty](./empty/)() const | ตรวจสอบว่าคอลเลคชัน delegate ว่างหรือไม่ |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | NOT IMPLEMENTED. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | เรียกใช้ delegate ทั้งหมดที่อยู่ในคอลเลคชันในขณะนี้. delegate จะถูกเรียกตามลำดับที่เพิ่มเข้ามาในคอลเลคชัน. วิธีการนี้จะบล็อกจนกว่า delegate ทั้งหมดจะทำงานเสร็จ |
| **bool** [IsNull](./isnull/)() const | ตรวจสอบว่าคอลเลคชัน delegate ว่างหรือไม่ |
|  [MulticastDelegate](./multicastdelegate/)() | สร้างคอลเลคชันว่าง |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | เทียบเท่ากับคอนสตรัคเตอร์เริ่มต้น |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | ทำสำเนาแบบตื้นของคอลเลคชัน delegate |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | คอนสตรัคเตอร์ย้าย |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | สร้างอินสแตนซ์และใส่ delegate ที่ระบุลงในคอลเลคชัน delegate |
|  [MulticastDelegate](./multicastdelegate/)(T) | สร้างอินสแตนซ์และใส่ค่าที่ระบุลงในคอลเลคชัน delegate |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | สร้างอินสแตนซ์และใส่ค่าที่ระบุลงในคอลเลคชัน delegate |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | ตรวจสอบว่าคอลเลคชัน delegate ไม่ว่าง |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | ตรวจสอบว่าตัวอย่างสองของ MulticastDelegate - อ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุ - ไม่เท่ากัน |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | เรียกใช้ delegate ทั้งหมดที่อยู่ในคอลเลคชันในขณะนี้. delegate จะถูกเรียกตามลำดับที่เพิ่มเข้ามาในคอลเลคชัน. ตัวดำเนินการจะบล็อกจนกว่า delegate ทั้งหมดจะทำงานเสร็จ |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | เพิ่ม delegate ที่ระบุลงในคอลเลคชัน |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | ลบ delegate ที่ระบุออกจากคอลเลคชัน delegate |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | กำหนดคอลเลคชันของ delegate ที่อ้างอิงโดยอ็อบเจ็กต์ที่ระบุให้กับอ็อบเจ็กต์ปัจจุบัน ทำให้ทั้งสองอ็อบเจ็กต์ชี้ไปยังคอลเลคชันเดียวกัน |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | ตัวดำเนินการกำหนดค่าแบบย้าย |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | ตรวจสอบว่าคอลเลคชัน delegate ว่าง |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | ตรวจสอบว่าตัวอย่างสองของ MulticastDelegate - อ็อบเจ็กต์ปัจจุบันและอ็อบเจ็กต์ที่ระบุ - เท่ากัน |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | ทำความสะอาด callback ที่ว่างเปล่า (ไม่เรียกอะไรจริง) |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | คืนค่าอ้างอิงไปยังอ็อบเจ็กต์ [TypeInfo](../typeinfo/) ที่แสดงข้อมูลประเภทคลาส MulticastDelegate |
|  [~MulticastDelegate](./~multicastdelegate/)() | ตัวทำลาย |
## การนิยามชนิด

| การนิยามชนิด | คำอธิบาย |
| --- | --- |
| [Callback](./callback/) | ประเภทของ delegate ที่เป็นตัวแทนของคลาส MulticastDelegate |
| [Function](./function/) | ประเภทของฟังก์ชันที่เกี่ยวข้องกับลายเซ็นของ delegate |
## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)