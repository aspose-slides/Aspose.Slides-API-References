---
title: AreSameImpl()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: Are-same-เปรียบเทียบตัวชี้อัจฉริยะ.
type: docs
weight: 79
url: /th/system.testpredicates/aresameimpl/
---
## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Are-same-compares smart pointers.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทวัตถุ LHS. |
| T2 | ประเภทวัตถุ RHS. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T1\& | ค่าของ LHS. |
| rhs | const T2\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ใช้เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่คืน

ผลลัพธ์การตรวจสอบแบบ gtest-styled.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, long long) function

Are-same-compares exceptions.

```cpp
template<typename T1,typename T2> std::enable_if<IsExceptionWrapper<T1>::value &&IsExceptionWrapper<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทวัตถุ LHS. |
| T2 | ประเภทวัตถุ RHS. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T1\& | ค่าของ LHS. |
| rhs | const T2\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ใช้เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่คืน

ผลลัพธ์การตรวจสอบแบบ gtest-styled.

## System::TestPredicates::AreSameImpl(const char *, const char *, const T1\&, const T2\&, int) function

Are-same-compares non-pointer values.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
```

### พารามิเตอร์เทมเพลต

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทวัตถุ LHS. |
| T2 | ประเภทวัตถุ RHS. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T1\& | ค่าของ LHS. |
| rhs | const T2\& | ค่าของ RHS. |

### ค่าที่คืน

ผลลัพธ์การตรวจสอบแบบ gtest-styled.

## ดูเพิ่มเติม

* โครงสร้าง [IsSmartPtr](../../system/issmartptr/)
* โครงสร้าง [IsExceptionWrapper](../../system/isexceptionwrapper/)
* เนมสเปซ [System::TestPredicates](../)
* ไลบรารี [Aspose.Slides](../../)