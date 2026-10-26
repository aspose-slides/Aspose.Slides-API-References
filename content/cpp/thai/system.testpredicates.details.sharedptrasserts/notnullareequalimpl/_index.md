---
title: NotNullAreEqualImpl()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: เปรียบเทียบความเท่าเทียมของอาเรย์หรือรายการ.
type: docs
weight: 40
url: /th/system.testpredicates.details.sharedptrasserts/notnullareequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1&, const T2&, long long) ฟังก์ชัน

เปรียบเทียบความเท่าเทียมของอาเรย์หรือรายการ

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทคอนเทนเนอร์ LHS |
| T2 | ประเภทคอนเทนเนอร์ RHS |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS |
| rhs_expr | const char * | นิพจน์ RHS |
| lhs | const T1\& | ค่า LHS |
| rhs | const T2\& | ค่า RHS |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เลือกการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่คืน

ผลลัพธ์การตรวจสอบในรูปแบบ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1&, const T2&, long long) ฟังก์ชัน

เปรียบเทียบความเท่าเทียมของอินสแตนซ์ IEnumerable

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทอิลเมนต์ LHS |
| T2 | ประเภทอิลเมนต์ RHS |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS |
| rhs_expr | const char * | นิพจน์ RHS |
| lhs | const T1\& | ค่า LHS |
| rhs | const T2\& | ค่า RHS |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เลือกการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่คืน

ผลลัพธ์การตรวจสอบในรูปแบบ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1&, const T2&, int32_t) ฟังก์ชัน

เปรียบเทียบความเท่าเทียมของประเภทที่ไม่ทราบโดยใช้เมธอด Equals

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทอ็อบเจ็กต์ LHS |
| T2 | ประเภทอ็อบเจ็กต์ RHS |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS |
| rhs_expr | const char * | นิพจน์ RHS |
| lhs | const T1\& | ค่า LHS |
| rhs | const T2\& | ค่า RHS |

### ค่าที่คืน

ผลลัพธ์การตรวจสอบในรูปแบบ gtest

## ดูเพิ่มเติม

* Typedef [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* Typedef [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* Struct [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* เนมสเปซ [System::TestPredicates::Details::SharedPtrAsserts](../)
* ไลบรารี [Aspose.Slides](../../)