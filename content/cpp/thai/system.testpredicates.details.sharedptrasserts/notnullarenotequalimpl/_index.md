---
title: NotNullAreNotEqualImpl()
second_title: Aspose.Slides สำหรับ C++ การอ้างอิง API
description: เปรียบเทียบไม่เท่ากับสำหรับอาร์เรย์หรือรายการ
type: docs
weight: 105
url: /th/system.testpredicates.details.sharedptrasserts/notnullarenotequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

เปรียบเทียบไม่เท่ากับสำหรับอาร์เรย์หรือรายการ

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทคอนเทนเนอร์ด้านซ้าย |
| T2 | ประเภทคอนเทนเนอร์ด้านขวา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS |
| rhs_expr | const char * | นิพจน์ RHS |
| lhs | const T1\& | ค่า LHS |
| rhs | const T2\& | ค่า RHS |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เลือกการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งกลับ

ผลลัพธ์การตรวจสอบสไตล์ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

เปรียบเทียบไม่เท่ากับสำหรับอินสแตนซ์ของ IEnumerable

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทองค์ประกอบด้านซ้าย |
| T2 | ประเภทองค์ประกอบด้านขวา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS |
| rhs_expr | const char * | นิพจน์ RHS |
| lhs | const T1\& | ค่า LHS |
| rhs | const T2\& | ค่า RHS |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เลือกการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งกลับ

ผลลัพธ์การตรวจสอบสไตล์ gtest

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) function

เปรียบเทียบไม่เท่ากับสำหรับประเภทที่ไม่ทราบโดยใช้เมธอด Eqauals

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทอ็อบเจ็กต์ด้านซ้าย |
| T2 | ประเภทอ็อบเจ็กต์ด้านขวา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS |
| rhs_expr | const char * | นิพจน์ RHS |
| lhs | const T1\& | ค่า LHS |
| rhs | const T2\& | ค่า RHS |

### ค่าที่ส่งกลับ

ผลลัพธ์การตรวจสอบสไตล์ gtest

## ดูเพิ่มเติม

* ประเภทนิยาม [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* ประเภทนิยาม [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* โครงสร้าง [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* เนมสเปซ [System::TestPredicates::Details::SharedPtrAsserts](../)
* ไลบรารี [Aspose.Slides](../../)