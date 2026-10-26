---
title: invoke()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: เรียกใช้ delegate ทั้งหมดที่อยู่ในคอลเลกชันของ delegate ปัจจุบัน. delegate จะถูกเรียกใช้ตามลำดับเดียวกับที่ถูกเพิ่มเข้ามาในคอลเลกชัน. วิธีการจะบล็อกอยู่ขณะ delegate กำลังทำงาน.
type: docs
weight: 222
url: /th/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/invoke/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes...) const เมธอด

เรียกใช้งานตัว delegate ทั้งหมดที่มีอยู่ในคอลเลกชันของ delegate ตัว delegate จะถูกเรียกใช้งานตามลำดับเดียวกับที่ถูกเพิ่มเข้ามาในคอลเลกชัน วิธีการจะบล็อกอยู่ในขณะที่ตัว delegate กำลังทำงาน

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes... args) const
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| args | ArgumentTypes... | arguments to pass to the delegates to be invoked |

### ค่าที่คืน

Return value of the last invoked delegate

## ดูเพิ่มเติม

* คลาส [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)