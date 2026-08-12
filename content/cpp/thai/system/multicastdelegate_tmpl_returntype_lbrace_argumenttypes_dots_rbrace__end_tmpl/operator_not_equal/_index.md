---
title: operator!=()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: กำหนดว่าการรวบรวม delegate ไม่เป็นค่าว่างหรือไม่.
type: docs
weight: 131
url: /th/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_not_equal/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator!=(const std::nullptr_t\&) const method

กำหนดว่าการรวบรวม delegate ไม่เป็นค่าว่างหรือไม่.

```cpp
bool System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator!=(const std::nullptr_t &) const
```

### ค่าที่ส่งคืน

True หากการรวบรวม delegate ไม่เป็นค่าว่าง, มิฉะนั้น - false

## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator!=(const MulticastDelegate\&) const method

กำหนดว่าตัวอย่างสองตัวของ MulticastDelegate - วัตถุปัจจุบันและวัตถุที่ระบุ - ไม่เท่ากันหรือไม่.

```cpp
bool System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator!=(const MulticastDelegate &other) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| other | const [MulticastDelegate](../multicastdelegate/)\& | วัตถุ MulticastDelegate ที่ใช้เปรียบเทียบกับ |

### ค่าที่ส่งคืน

True หากวัตถุทั้งสองแสดงถึงการรวบรวม delegates เดียวกัน, มิฉะนั้น - false

## ดูเพิ่มเติม

* เมธอด [MulticastDelegate](../multicastdelegate/)
* คลาส [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)