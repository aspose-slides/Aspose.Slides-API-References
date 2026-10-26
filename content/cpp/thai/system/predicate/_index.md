---
title: Predicate
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: แทนค่าตัวชี้ไปยัง predicate - เอนทิตี้ที่สามารถเรียกใช้ได้ซึ่งรับอาร์กิวเมนต์เดียวและส่งคืนค่า bool
type: docs
weight: 4187
url: /th/system/predicate/
---
## typedef ของ Predicate


แทนค่าตัวชี้ไปยัง predicate - เอนทิตี้ที่สามารถเรียกใช้ได้ซึ่งรับอาร์กิวเมนต์เดียวและส่งคืนค่า bool.

```cpp
using System::Predicate = typedef MulticastDelegate<bool(T)>
```

## หมายเหตุ



```cpp
#include "system/array.h"
#include "system/predicate.h"
#include <iostream>

int main()
{
  // เติมอาร์เรย์.
  auto arr = System::MakeArray<int>({-1, -123, 5, 3, 7});

  // สร้าง predicate ที่คืนค่าองค์ประกอบของอาร์เรย์ที่มากกว่า 3.
  const auto predicate = static_cast<System::Predicate<int>>([](int a) -> bool
  {
      return a > 3;
  });

  // ค้นหาองค์ประกอบแรกของอาร์เรย์โดยใช้ predicate ที่สร้างขึ้นและพิมพ์มัน.
  int firstItem = System::Array<int>::Find(arr, predicate);
  std::cout << firstItem << std::endl;

  return 0;
}
/*
ตัวอย่างโค้ดนี้ให้ผลลัพธ์ต่อไปนี้:
5
*/
```

## ดูเพิ่มเติม

* Namespace [System](../)
* Library [Aspose.Slides](../../)