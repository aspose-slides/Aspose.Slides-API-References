---
title: AreNotSame()
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ C++
description: Are-not-same เปรียบเทียบอาร์กิวเมนต์สำหรับการแปลการตรวจสอบ AreSame.
type: docs
weight: 92
url: /th/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) ฟังก์ชัน

Are-not-same เปรียบเทียบอาร์กิวเมนต์สำหรับการตรวจสอบ AreSame

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T1 | ประเภทวัตถุ LHS. |
| T2 | ประเภทวัตถุ RHS. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T1\& | ค่า LHS. |
| rhs | const T2\& | ค่า RHS. |

### ค่าที่ส่งกลับ

gtest-styled assertion result.

## ดูเพิ่มเติม

* เนมสเปซ [System::TestPredicates](../)
* ไลบรารี [Aspose.Slides](../../)