---
title: Action
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: ประเภท delegate ที่อ้างอิงเมธอดที่ไม่มีค่ารีเทิร์น
type: docs
weight: 3602
url: /th/system/action/
---
## Action typedef

ประเภท delegate ที่อ้างอิงเมธอดที่ไม่มีค่ารีเทิร์น

```cpp
using System::Action = typedef MulticastDelegate<void(Args...)>
```

## หมายเหตุ



```cpp
#include <system/action.h>

using namespace System;

// ฟังก์ชันที่พิมพ์สตริงที่ส่งเข้ามา.
void PrintString(const String &string)
{
  using namespace std;
  cout << string << endl;
}

int main()
{
  // สร้างอินสแตนซ์ของ Action.
  auto action = Action<String>(std::bind(&PrintString, std::placeholders::_1));

  // เรียกใช้ action.
  action(u"Hello, world!");

  return 0;
}
/*
ตัวอย่างโค้ดนี้แสดงผลลัพธ์ต่อไปนี้:
Hello, world!
*/
```

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)