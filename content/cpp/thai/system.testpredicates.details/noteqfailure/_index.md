---
title: NotEqFailure()
second_title: Aspose.Slides สำหรับอ้างอิง API ของ C++
description: แสดงข้อผิดพลาดการตรวจสอบ != สำหรับผลลัพธ์.
type: docs
weight: 40
url: /th/system.testpredicates.details/noteqfailure/
---
## System::TestPredicates::Details::NotEqFailure(const char *, const char *, T1\&, T2\&) function

แสดงผลการล้มเหลวของการตรวจสอบ !=.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotEqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทค่าด้านซ้าย |
| T2 | ประเภทค่าด้านขวา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ด้านซ้าย |
| rhs_expr | const char * | นิพจน์ด้านขวา |
| lhs | T1\& | ค่าด้านซ้าย |
| rhs | T2\& | ค่าด้านขวา |

### ค่าที่ส่งกลับ

[Object](../../system/object/) ข้อความการล้มเหลวที่ห่อหุ้ม.

## ดูเพิ่มเติม

* เนมสเปซ [System::TestPredicates::Details](../)
* ไลบรารี [Aspose.Slides](../../)