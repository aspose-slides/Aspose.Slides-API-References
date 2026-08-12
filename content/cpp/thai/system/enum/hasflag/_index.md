---
title: HasFlag()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: กำหนดว่าบิตที่ระบุถูกตั้งค่าในรูปแบบบิตของค่าตัวแปร enum ที่ระบุหรือไม่
type: docs
weight: 14
url: /th/system/enum/hasflag/
---
## Enum::HasFlag(E, E) เมธอด


Determines if the specified bits are set in a bitary representation of the specified enum value.

```cpp
static bool System::Enum<E, Guard>::HasFlag(E value, E mask)
```


### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | E | ค่าของ enum เพื่อตรวจสอบ |
| mask | E | มาสก์เพื่อเปรียบเทียบบิตของ value |

### ค่าที่คืน

True if bits that are set in **mask** are also set in **value**, otherwise - false

## ดูเพิ่มเติม

* โครงสร้าง [Enum](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)