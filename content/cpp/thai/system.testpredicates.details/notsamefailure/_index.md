---
title: NotSameFailure()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: จัดรูปแบบข้อผิดพลาดการตรวจสอบ 'not same' สำหรับการแสดงผล.
type: docs
weight: 66
url: /th/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) ฟังก์ชัน

จัดรูปแบบข้อผิดพลาดการตรวจสอบ 'ไม่เหมือนกัน' สำหรับการแสดงผล.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ชนิดค่าด้านซ้าย |
| T2 | ชนิดค่าด้านขวา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ด้านซ้าย |
| rhs_expr | const char * | นิพจน์ด้านขวา |
| lhs | T1\& | ค่าด้านซ้าย |
| rhs | T2\& | ค่าด้านขวา |

### ค่าที่ส่งคืน

[Object](../../system/object/) ข้อความการล้อมข้อผิดพลาด.

## ดูเพิ่มเติม

* เนมสเปซ [System::TestPredicates::Details](../)
* ไลบรารี [Aspose.Slides](../../)