---
title: Equals()
second_title: Aspose.Slides สำหรับ API ของ C++
description: กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันเท่ากับค่าที่แสดงโดยอ็อบเจกต์ Nullable ที่ระบุหรือไม่
type: docs
weight: 131
url: /th/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const เมธอด

กำหนดว่าค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันเท่ากับค่าที่แสดงโดยอ็อบเจกต์ [Nullable](../) ที่ระบุหรือไม่

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทพื้นฐานของอ็อบเจกต์ [Nullable](../) ที่จะเปรียบเทียบกับ |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | const T1\& | การอ้างอิงคงที่ไปยังอ็อบเจกต์ [Nullable](../) เพื่อเปรียบเทียบกับ |

### ค่าที่ส่งคืน

เป็นจริงหากค่าที่แสดงโดยอ็อบเจกต์ปัจจุบันเท่ากับค่าที่แสดงโดยอ็อบเจกต์ [Nullable](../) ที่ระบุ, มิฉะนั้น - เท็จ

## ดูเพิ่มเติม

* คลาส [Nullable](../)
* โครงสร้าง [IsNullable](../../isnullable/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)