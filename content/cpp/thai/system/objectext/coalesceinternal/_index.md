---
title: CoalesceInternal()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: การทำงานของการแปลงตัวดำเนินการ '??' สำหรับประเภทที่ไม่เป็น null. โหลดสำหรับกรณีที่ RT2 สามารถแปลงเป็น RT1 ได้.
type: docs
weight: 157
url: /th/system/objectext/coalesceinternal/
---
## ObjectExt::CoalesceInternal(RT1, F) เมธอด

การทำงานของการแปลงตัวดำเนินการ '??' สำหรับประเภทที่ไม่เป็น null. โหลดสำหรับกรณีที่ RT2 สามารถแปลงเป็น RT1 ได้.

```cpp
template<typename RT1,typename RT2,typename F> static std::conditional<std::is_convertible<RT2, RT1>::value, RT1, RT2>::type System::ObjectExt::CoalesceInternal(RT1 value, F func)
```

### พารามิเตอร์ของเทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T0 | ชนิดค่าด้านซ้าย. |
| T1 | ชนิดของ lambda ที่ห่อหุ้มนิพจน์ RHS. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | RT1 | ค่าด้านซ้าย. |
| func | F | นิพจน์ RHS. |

### ค่าที่ส่งคืน

ถ้าค่าด้านซ้ายไม่เป็นค่าว่าง, จะคืนค่าด้านซ้าย, มิฉะนั้นจะคำนวณนิพจน์ RHS และคืนผลลัพธ์.

## ดูเพิ่มเติม

* คลาส [ObjectExt](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)