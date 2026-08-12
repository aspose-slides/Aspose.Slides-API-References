---
title: Delegate< ReturnType(ArgumentTypes...)>
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: "แทนที่ตัวชี้ไปยังฟังก์ชัน, เมธอด หรืออ็อบเจกต์ฟังก์ชัน. ประเภทนี้ควรจัดสรรบนสแต็กและส่งให้ฟังก์ชันโดยค่า หรือโดยการอ้างอิง. อย่าใช้คลาส System::SmartPtr เพื่อจัดการอ็อบเจกต์ของประเภทนี้."
type: docs
weight: 287
url: /th/system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## Delegate< ReturnType(ArgumentTypes...)> คลาส

แทนที่ตัวชี้ไปยังฟังก์ชัน, เมธอด หรืออ็อบเจกต์ฟังก์ชัน. ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านให้ฟังก์ชันโดยค่า หรือโดยการอ้างอิง. อย่าใช้คลาส [System::SmartPtr](../smartptr/) เพื่อจัดการอ็อบเจกต์ของประเภทนี้.

```cpp
template<class ReturnType,class...>class Delegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| ReturnType | ประเภทค่าที่ส่งกลับของฟังก์ชัน, เมธอด หรืออ็อบเจกต์ฟังก์ชันที่ตัวชี้แสดงโดยคลาสนี้ |
| ArgumentTypes | รายการอาร์กิวเมนต์ของฟังก์ชัน, เมธอด หรืออ็อบเจกต์ฟังก์ชันที่ตัวชี้แสดงโดยคลาสนี้ |

## เมธอด

| Method | Description |
| --- | --- |
|  [Delegate](./delegate/)() | ตัวสร้างค่าเริ่มต้น. สร้างอ็อบเจกต์ delegate ที่ไม่ได้ชี้ไปยังสิ่งใด |
|  [Delegate](./delegate/)(const Delegate\&) |  |
|  [Delegate](./delegate/)(Delegate\&&) | คอนสตรัคเตอร์คัดลอกแบบย้าย. รับความเป็นเจ้าของของเอนทิตี้ที่ตัวชี้ของ delegate ที่ระบุชี้ไป |
|  [Delegate](./delegate/)(T, typename std::enable_if<\!std::is_bind_expression\<T\>::value\&&std::is_pointer\<T\>::value\&&std::is_function\<typename std::remove_pointer\<T\>::type\>::value\>::type *) | คอนสตรัคเตอร์. สร้างอ็อบเจกต์ delegate จากพอยเตอร์ที่ระบุไปยังฟังก์ชันอิสระหรือเมธอด static |
|  [Delegate](./delegate/)(T, typename std::enable_if\<std::is_bind_expression\<T\>::value\>::type *) | คอนสตรัคเตอร์. สร้าง delegate จากพอยเตอร์ที่ระบุไปยังอ็อบเจกต์ฟังก์ชันที่สร้างโดย std::bind() |
|  [Delegate](./delegate/)(int, T\&) | คอนสตรัคเตอร์. สร้าง delegate จากอ็อบเจกต์ฟังก์ชันที่ระบุ |
|  [Delegate](./delegate/)(long, T\&&) | คอนสตรัคเตอร์แบบย้าย. สร้าง delegate จากอ็อบเจกต์ฟังก์ชันที่ระบุ |
|  [Delegate](./delegate/)(MemberType ClassType::*, ClassType *) | คอนสตรัคเตอร์. สร้าง delegate ที่ชี้ไปยังเมธอด non-static ที่ระบุของอ็อบเจกต์ที่ระบุ |
|  [Delegate](./delegate/)(MemberType MemberClass::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | คอนสตรัคเตอร์. สร้าง delegate ที่ชี้ไปยังเมธอด non-static ที่ระบุของอ็อบเจกต์ที่ระบุ |
|  [Delegate](./delegate/)(std::function\<R(Args...)>) | สร้างอ็อบเจกต์ delegate ที่ชี้ไปยังอ็อบเจกต์ฟังก์ชัน std::function |
| **bool** [Empty](./empty/)() const | กำหนดว่าอ็อบเจกต์ delegate ปัจจุบันว่างเปล่าหรือไม่, เช่น ไม่ชี้ไปยังเอนทิตี้ใด |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | เรียกใช้งานฟังก์ชัน, เมธอด หรืออ็อบเจกต์ฟังก์ชันที่ตัวชี้ของอ็อบเจกต์ delegate ปัจจุบันชี้ไป |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)(const [Delegate](./delegate/)\&) |  |
| [Delegate](./delegate/)\& [operator=](./operator_equal/)([Delegate](./delegate/)\&&) | ตัวดำเนินการกำหนดค่าแบบย้าย. รับความเป็นเจ้าของของเอนทิตี้ที่ตัวชี้ของ delegate ที่ระบุชี้ไป |
| **bool** [operator==](./operator_equal_equal/)(const [Delegate](./delegate/)\&) const | เปรียบเทียบอ็อบเจกต์ delegate สองตัวเพื่อตรวจสอบว่าพวกมันชี้ไปยังเอนทิตี้เดียวกันหรือไม่ |

## หมายเหตุ



```cpp
#include "system/delegate.h"
#include <iostream"

// ประกาศ delegate.
using Message = System::Delegate<void()>;

void PrintMessage()
{
  std::cout << "Hello, world!" << std::endl;
}

int main()
{
  // กำหนดให้ตัวแปรเป็นที่อยู่ของฟังก์ชัน PrintMessage.
  Message mes = Message(&PrintMessage);

  // เรียกใช้ฟังก์ชัน.
  mes();

  return 0;
}
/*
ตัวอย่างโค้ดนี้สร้างผลลัพธ์ต่อไปนี้:
สวัสดี, โลก!
*/
```

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)