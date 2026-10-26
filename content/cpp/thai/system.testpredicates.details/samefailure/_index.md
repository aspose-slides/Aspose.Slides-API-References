---
title: SameFailure()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: จัดรูปแบบข้อผิดพลาดการตรวจสอบ 'same' สำหรับการแสดงผล.
type: docs
weight: 53
url: /th/system.testpredicates.details/samefailure/
---
## System::TestPredicates::Details::SameFailure(const char *, const char *, T1\&, T2\&) ฟังก์ชัน

จัดรูปแบบข้อผิดพลาดการตรวจสอบ 'same' สำหรับการแสดงผล.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T1 | ประเภทค่าด้านซ้าย. |
| T2 | ประเภทค่าด้านขวา. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ด้านซ้าย. |
| rhs_expr | const char * | นิพจน์ด้านขวา. |
| lhs | T1\& | ค่าด้านซ้าย. |
| rhs | T2\& | ค่าด้านขวา. |

### ค่าที่ส่งกลับ

[Object](../../system/object/) ห่อข้อความข้อผิดพลาด.

## ดูเพิ่มเติม

* เนมสเปซ [System::TestPredicates::Details](../)
* ไลบรารี [Aspose.Slides](../../)