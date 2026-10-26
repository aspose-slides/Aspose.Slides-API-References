---
title: Coalesce()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: การแปลตัวดำเนินการ '??' สำหรับประเภทที่ไม่เป็นค่า null
type: docs
weight: 170
url: /th/system/objectext/coalesce/
---
## ObjectExt::Coalesce(T0, T1) เมธอด

การแปลงตัวดำเนินการ '??' สำหรับชนิดที่ไม่เป็นค่า null

```cpp
template<typename T0,typename T1> static auto System::ObjectExt::Coalesce(T0 value, T1 func)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | T0 | LHS value. |
| func | T1 | RHS expression. |

### ค่าที่ส่งกลับ

ถ้าค่า LHS ไม่เป็น null จะคืนค่า LHS, หากไม่เช่นนั้นจะคำนวณนิพจน์ RHS และคืนผลลัพธ์

## ObjectExt::Coalesce(System::Nullable\<T0\>, T1) เมธอด

การแปลงตัวดำเนินการ '??' สำหรับชนิดที่เป็นค่า null

```cpp
template<typename T0,typename T1> static T0 System::ObjectExt::Coalesce(System::Nullable<T0> value, T1 func)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T0 | LHS value type. |
| T1 | Type of lambda encapsulating RHS expression. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [System::Nullable](../../nullable/)\<T0\> | LHS value. |
| func | T1 | RHS expression. |

### ค่าที่ส่งกลับ

ถ้าค่า LHS ไม่เป็น null จะคืนค่า LHS, หากไม่เช่นนั้นจะคำนวณนิพจน์ RHS และคืนผลลัพธ์

## ดูเพิ่มเติม

* คลาส [ObjectExt](../)
* คลาส [Nullable](../../nullable/)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)