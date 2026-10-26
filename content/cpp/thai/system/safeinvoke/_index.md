---
title: SafeInvoke()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: การแปลการใช้ตัวดำเนินการ '?.'.
type: docs
weight: 2653
url: /th/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) ฟังก์ชัน

การแปลการใช้ตัวดำเนินการ '?.'

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T0 | ประเภทของนิพจน์ |
| T1 | ประเภทของลัมบ์ดาที่ห่อหุ้มนิพจน์ 'WhenTrue' |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| expr | T0\&& | ค่าของนิพจน์ |
| func | T1\&& | นิพจน์ 'WhenTrue' ที่ผูกกับฟันก์เตอร์ |

### ค่าที่ส่งคืน

หากค่าของ expr ไม่เป็น null จะคืนค่า func ที่ถูกเรียกด้วยค่าของมันเป็นอาร์กิวเมนต์แรก มิฉะนั้นจะคืนค่า null.

## ดูเพิ่มเติม

* เนมสเปซ [System](../)
* ไลบรารี [Aspose.Slides](../../)