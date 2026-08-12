---
title: Func
second_title: Aspose.Slides สำหรับการอ้างอิง API C++
description: "ตัวแทนฟังก์ชัน ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่าหรือโดยการอ้างอิง ไม่ควรใช้คลาส System::SmartPtr เพื่อจัดการออบเจ็กต์ของประเภทนี้."
type: docs
weight: 859
url: /th/system/func/
---
## Func คลาส

ตัวแทนฟังก์ชัน ประเภทนี้ควรจัดสรรบนสแตกและส่งผ่านไปยังฟังก์ชันโดยค่าหรือโดยการอ้างอิง ไม่ควรใช้คลาส [System::SmartPtr](../smartptr/) เพื่อจัดการวัตถุของประเภทนี้.

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| Args | อาร์กิวเมนต์ในการเรียกใช้ จากนั้นประเภทค่าที่ต้องส่งกลับ |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
|  [Func](./func/)() | คอนสตรักเตอร์เริ่มต้นที่สร้าง null-Func. |
|  [Func](./func/)(T\&&) | คอนสตรักเตอร์ที่สร้างอ็อบเจ็กต์ [Func](./) และกำหนดค่า (ไม่ว่าจะเป็น callback จริงหรือ nullptr) ให้กับมัน. |
|  [Func](./func/)(const [Func](./)\&) | คอนสตรักเตอร์คัดลอก. |
|  [Func](./func/)([Func](./)\&&) | คอนสตรักเตอร์ย้าย. |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | การกำหนดค่าโดยคัดลอกร. |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | การกำหนดค่าด้วยการย้าย. |
|  [~Func](./~func/)() | ดีสตรักเตอร์. |

## หมายเหตุ



```cpp
#include "system/func.h"
#include <iostream"

// ฟังก์ชันนี้รับอินสแตนซ์ของ delegate System::Func เป็นพารามิเตอร์.
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // สร้างอินสแตนซ์ของ delegate System::Func.
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // ส่งอินสแตนซ์ที่สร้างไปเป็นอาร์กิวเมนต์ของฟังก์ชัน.
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
ตัวอย่างโค้ดนี้สร้างผลลัพธ์ต่อไปนี้:
1
4
9
*/
```

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)