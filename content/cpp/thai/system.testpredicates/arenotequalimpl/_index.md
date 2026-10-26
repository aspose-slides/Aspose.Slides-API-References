---
title: AreNotEqualImpl()
second_title: Aspose.Slides สำหรับ C++ API อ้างอิง
description: การเปรียบเทียบที่ไม่เท่ากันเปรียบเทียบค่าหนึ่งหรือทั้งสองค่าที่เป็น Decimal.
type: docs
weight: 53
url: /th/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) ฟังก์ชัน

การเปรียบเทียบที่ไม่เท่ากันเปรียบเทียบค่าหนึ่งหรือทั้งสองค่าโดยที่ [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T1\& | ค่าของ LHS. |
| rhs | const T2\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่คืนกลับ

ผลลัพธ์การอ้างอิงแบบ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) ฟังก์ชัน

การเปรียบเทียบที่ไม่เท่ากันเปรียบเทียบสองค่าของ [System::String](../../system/string/) โดยป้องกันการเรียกใช้ฟังก์ชันสมาชิกบน [String](../../system/string/) ที่เป็นค่าว่าง. แม่แบบสำหรับเหตุผลการยกเว้นแบบ deduction เหมือนกับการโอเวอร์โหลด AreEqualImpl [String](../../system/string/) ด้านบน.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) ประเภท, จำกัดให้เป็น [System::String](../../system/string/). |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T\& | ค่าของ LHS. |
| rhs | const T\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่คืนกลับ

ผลลัพธ์การอ้างอิงแบบ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) ฟังก์ชัน

การเปรียบเทียบที่ไม่เท่ากันเปรียบเทียบประเภทที่ไม่ใช่พอยน์เตอร์โดยใช้เมธอด Equals ที่ให้มา.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T\& | ค่าของ LHS. |
| rhs | const T\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่คืนกลับ

ผลลัพธ์การอ้างอิงแบบ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) ฟังก์ชัน

การเปรียบเทียบที่ไม่เท่ากันเปรียบเทียบประเภทที่ไม่ใช่พอยน์เตอร์โดยใช้เมธอด Equals ที่ให้มา.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | T\& | ค่าของ LHS. |
| rhs | const T\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่คืนกลับ

ผลลัพธ์การอ้างอิงแบบ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) ฟังก์ชัน

การเปรียบเทียบที่ไม่เท่ากันเปรียบเทียบประเภทที่ไม่ใช่พอยน์เตอร์โดยใช้ตัวดำเนินการ != ที่ให้มา.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T\& | ค่าของ LHS. |
| rhs | const T\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่คืนกลับ

ผลลัพธ์การอ้างอิงแบบ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) ฟังก์ชัน

การเปรียบเทียบที่ไม่เท่ากันเปรียบเทียบ boxable กับค่า [SmartPtr](../../system/smartptr/) โดยใช้การอันบ็อกซ์.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | T | ค่าของ LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่คืนกลับ

ผลลัพธ์การอ้างอิงแบบ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) ฟังก์ชัน

การเปรียบเทียบที่ไม่เท่ากันเปรียบเทียบ boxable กับค่า [SmartPtr](../../system/smartptr/) โดยใช้การอันบ็อกซ์.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | ค่าของ LHS. |
| rhs | T | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่คืนกลับ

ผลลัพธ์การอ้างอิงแบบ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) ฟังก์ชัน

การเปรียบเทียบที่ไม่เท่ากันเปรียบเทียบประเภทสุ่มกับ nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | T | ค่าของ LHS. |
| s | std::nullptr_t | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่คืนกลับ

ผลลัพธ์การอ้างอิงแบบ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) ฟังก์ชัน

การเปรียบเทียบที่ไม่เท่ากันเปรียบเทียบประเภทสุ่มกับ nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T | [Object](../../system/object/) type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| rhs | std::nullptr_t | ค่าของ RHS. |
| s | T | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่ของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่คืนกลับ

ผลลัพธ์การอ้างอิงแบบ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) ฟังก์ชัน

การเปรียบเทียบที่เท่ากันเปรียบเทียบประเภทพอยน์เตอร์.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T1\& | ค่าของ LHS. |
| rhs | const T2\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่ของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่คืนกลับ

ผลลัพธ์การอ้างอิงแบบ gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) ฟังก์ชัน

การเปรียบเทียบที่เท่ากันเปรียบเทียบประเภทสุ่มโดยใช้ gtest altorithms.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### พารามิเตอร์แม่แบบ

| Parameter | Description |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### อาร์กิวเมนต์

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | T1 | ค่าของ LHS. |
| rhs | T2 | ค่าของ RHS. |

### ค่าที่คืนกลับ

ผลลัพธ์การอ้างอิงแบบ gtest.

## ดูเพิ่มเติม

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [String](../../system/string/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)