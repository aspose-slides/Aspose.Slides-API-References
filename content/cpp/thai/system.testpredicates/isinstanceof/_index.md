---
title: IsInstanceOf()
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ C++
description: Is-instance-of-เปรียบเทียบอาร์กิวเมนต์สำหรับการแปลการอ้างอิงของ IsInstanceOf
type: docs
weight: 118
url: /th/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const TypeInfo\&, const T\&) ฟังก์ชัน

Is-instance-of-เปรียบเทียบอาร์กิวเมนต์สำหรับการอ้างอิง IsInstanceOf

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```

### พารามิเตอร์เทมเพลต

| Parameter | Description |
| --- | --- |
| T | ประเภทของอาร์กิวเมนต์ |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ด้านซ้าย |
| rhs_expr | const char * | นิพจน์ด้านขวา |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | วัตถุ typeInfo ที่แสดงถึงประเภทที่ต้องเปรียบเทียบกับประเภทของ **obj** |
| obj | const T\& | วัตถุที่ต้องเปรียบเทียบประเภทกับประเภทที่ระบุ |

### ค่าที่ส่งกลับ

ผลลัพธ์การยืนยันแบบ gtest

## ดูเพิ่มเติม

* คลาส [TypeInfo](../../system/typeinfo/)
* เนมสเปซ [System::TestPredicates](../)
* ไลบรารี [Aspose.Slides](../../)