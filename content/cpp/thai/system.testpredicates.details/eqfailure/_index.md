---
title: EqFailure()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: จัดรูปแบบข้อความล้มเหลวของการอ้างอิง == สำหรับการแสดงผล.
type: docs
weight: 27
url: /th/system.testpredicates.details/eqfailure/
---
## System::TestPredicates::Details::EqFailure(const char *, const char *, T1\&, T2\&) function

จัดรูปแบบข้อความล้มเหลวของการอ้างอิง == สำหรับการแสดงผล.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::EqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทค่าด้านซ้าย (LHS). |
| T2 | ประเภทค่าด้านขวา (RHS). |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | T1\& | ค่า LHS. |
| rhs | T2\& | ค่า RHS. |

### ค่าที่ส่งคืน

[Object](../../system/object/) ข้อความล้มเหลวที่ห่อหุ้ม.

## ดูเพิ่มเติม

* เนมสเปซ [System::TestPredicates::Details](../)
* ไลบรารี [Aspose.Slides](../../)