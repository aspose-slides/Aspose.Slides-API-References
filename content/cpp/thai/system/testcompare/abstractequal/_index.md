---
title: AbstractEqual()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เปรียบเทียบคอลเลกชันสองชุดที่มีชนิดไม่ทราบค่า.
type: docs
weight: 14
url: /th/system/testcompare/abstractequal/
---
## TestCompare::AbstractEqual(SCG::ICollection\<T\> *const, SCG::ICollection\<T\> *const) method


เปรียบเทียบคอลเลกชันสองชุดที่มีชนิดไม่ทราบค่า.

```cpp
template<typename T> static bool System::TestCompare::AbstractEqual(SCG::ICollection<T> *const collA, SCG::ICollection<T> *const collB)
```


### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภทขององค์ประกอบคอลเลกชัน. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| collA | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | LHS คอลเลกชัน. |
| collB | [SCG::ICollection](../../../system.collections.generic/icollection/)\<T\> *const | RHS คอลเลกชัน. |

### ค่าที่ส่งคืน

true หากคอลเลกชันตรงกัน (เช่น ทั้งสองเป็น null) หรือหากขนาดตรงกันและอีลีเมนต์ตรงกัน, false มิฉะนั้น.

## ดูเพิ่มเติม

* คลาส [ICollection](../../../system.collections.generic/icollection/)
* โครงสร้าง [TestCompare](../)
* เนมสเปซ [System](../../)
* ไลบรารี [Aspose.Slides](../../../)