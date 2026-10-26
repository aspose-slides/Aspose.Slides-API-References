---
title: CoalesceAssign()
second_title: Aspose.Slides สำหรับ C++ อ้างอิง API
description: การแปลการทำงานของตัวดำเนินการ '??='.
type: docs
weight: 183
url: /th/system/objectext/coalesceassign/
---
## ObjectExt::CoalesceAssign(T0\&, T1) เมธอด


การแปลตัวดำเนินการ '??='

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::CoalesceAssign(T0 &value, T1 func) -> T0 &
```


### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T0 | ประเภทของค่า LHS. |
| T1 | ประเภทของ lambda ที่ห่อหุ้มนิพจน์ RHS. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| value | T0\& | ค่า LHS. |
| func | T1 | นิพจน์ RHS. |

### ค่าที่คืน

ถ้าค่า LHS ไม่เป็น null จะคืนค่า LHS, มิฉะนั้นจะคำนวณนิพจน์ RHS และคืนผลลัพธ์.

## ดูเพิ่มเติม

* คลาส [ObjectExt](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)