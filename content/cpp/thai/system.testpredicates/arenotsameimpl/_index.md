---
title: AreNotSameImpl()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เปรียบเทียบ smart pointers ที่ไม่เท่ากัน.
type: docs
weight: 105
url: /th/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, long long) ฟังก์ชัน

เปรียบเทียบ smart pointer ที่ไม่เท่ากัน.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### พารามิเตอร์เทมเพลต

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
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่า của พารามิเตอร์จะถูกละเว้น |

### ค่าที่คืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1\&, const T2\&, int) ฟังก์ชัน

เปรียบเทียบค่าที่ไม่ใช่ pointer ที่ไม่เท่ากัน.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```


### พารามิเตอร์เทมเพลต

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

### ค่าที่คืน

ผลลัพธ์การตรวจสอบแบบ gtest

## ดูเพิ่มเติม

* โครงสร้าง [IsSmartPtr](../../system/issmartptr/)
* เนมสเปซ [System::TestPredicates](../)
* ไลบรารี [Aspose.Slides](../../)