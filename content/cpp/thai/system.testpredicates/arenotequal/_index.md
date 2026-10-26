---
title: AreNotEqual()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: การเปรียบเทียบแบบไม่เท่ากับอาร์กิวเมนต์สำหรับการตรวจสอบ AreEqual
type: docs
weight: 40
url: /th/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1&&, T2&&) ฟังก์ชัน

การเปรียบเทียบไม่เท่ากับอาร์กิวเมนต์สำหรับการตรวจสอบ AreEqual.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทของอ็อบเจ็กต์ LHS. |
| T2 | ประเภทของอ็อบเจ็กต์ RHS. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | T1&& | ค่า LHS. |
| rhs | T2&& | ค่า RHS. |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest.

## ดูเพิ่มเติม

* เนมสเปซ [System::TestPredicates](../)
* ไลบรารี [Aspose.Slides](../../)