---
title: Boolean
second_title: Aspose.Slides สำหรับ C++ API Reference
description: คลาสที่เก็บสมาชิกแบบ static ของประเภท System.Boolean .Net
type: docs
weight: 79
url: /th/system/boolean/
---
## คลาส Boolean

คลาสที่เก็บสมาชิกแบบ static ของ [System.Boolean](./) .[Net](../../system.net/) ประเภท.

```cpp
class Boolean
```

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | แปลงสตริงที่ระบุให้เป็นค่าประเภท bool |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | แปลงสตริงที่ระบุให้เป็นค่าประเภท bool |

## ฟิลด์

| ฟิลด์ | คำอธิบาย |
| --- | --- |
| static [FalseString](./falsestring/) | การแทนค่า [String](../string/) ของค่า boolean ‘false’ |
| static [TrueString](./truestring/) | การแทนค่า [String](../string/) ของค่า boolean ‘true’ |

## หมายเหตุ



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // สร้างตัวแปร boolean
  bool isWeekend = false;

  // แยกวิเคราะห์สตริงอินพุตและพิมพ์ผลลัพธ์
  if (Boolean::TryParse(u"True", isWeekend))
  {
    std::cout << "Is weekend: " << (isWeekend ? "Yes" : "No");
  }
  else
  {
    std::cerr << "Something went wrong" << std::endl;
  }

  return 0;
}
/*
ตัวอย่างโค้ดนี้สร้างผลลัพธ์ต่อไปนี้:
วันหยุด: ใช่
*/
```

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)