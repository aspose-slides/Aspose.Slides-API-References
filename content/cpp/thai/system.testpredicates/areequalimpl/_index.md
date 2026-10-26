---
title: AreEqualImpl()
second_title: Aspose.Slides สำหรับ C++ API Reference
description: เปรียบเทียบเท่ากับค่าจุดลอยกับประเภทเชิงคณิตศาสตร์.
type: docs
weight: 27
url: /th/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) ฟังก์ชัน

เปรียบเทียบเท่ากับค่าจุดลอยกับประเภทเชิงคณิตศาสตร์.

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T1 | ประเภทวัตถุ LHS. |
| T2 | ประเภทวัตถุ RHS. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T1 | ค่า LHS. |
| rhs | const T2 | ค่า RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการกำหนดการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) ฟังก์ชัน

เปรียบเทียบค่าที่หนึ่งหรือทั้งสองเป็น [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T1 | ประเภทวัตถุ LHS. |
| T2 | ประเภทวัตถุ RHS. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T1& | ค่า LHS. |
| rhs | const T2& | ค่า RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการกำหนดการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T&, const T&, long long) ฟังก์ชัน

เปรียบเทียบประเภทที่ไม่ใช่พอยน์เตอร์โดยใช้เมธอด Equals ที่ให้ไว้.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T | [Object](../../system/object/) type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T& | ค่า LHS. |
| rhs | const T& | ค่า RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการกำหนดการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T&, const T&, long long) ฟังก์ชัน

เปรียบเทียบประเภทที่ไม่ใช่พอยน์เตอร์โดยใช้เมธอด Equals ที่ให้ไว้.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T | [Object](../../system/object/) type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | T& | ค่า LHS. |
| rhs | const T& | ค่า RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการกำหนดการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T&, const T&, long long) ฟังก์ชัน

เปรียบเทียบประเภทที่ไม่ใช่พอยน์เตอร์โดยใช้ตัวดำเนินการ == ที่ให้ไว้.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T | [Object](../../system/object/) type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T& | ค่า LHS. |
| rhs | const T& | ค่า RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการกำหนดการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>&, long long) ฟังก์ชัน

เปรียบเทียบแบบ boxable กับค่าของ [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T | [Object](../../system/object/) type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | T | ค่า LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)>& | ค่า RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการกำหนดการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>&, T, long long) ฟังก์ชัน

เปรียบเทียบแบบ boxable กับค่าของ [SmartPtr](../../system/smartptr/).

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T | [Object](../../system/object/) type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)>& | ค่า LHS. |
| rhs | T | ค่า RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการกำหนดการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>&, long long) ฟังก์ชัน

เปรียบเทียบสตริงลิเทรัลกับค่าของ [SmartPtr](../../system/smartptr/) โดยใช้การ unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const char16_t * | ค่า LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)>& | ค่า RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการกำหนดการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>&, const char16_t *, long long) ฟังก์ชัน

เปรียบเทียบสตริงลิเทรัลกับค่าของ [SmartPtr](../../system/smartptr/) โดยใช้การ unboxing.

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)<[Object](../../system/object/)>& | ค่า LHS. |
| rhs | const char16_t * | ค่า RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการกำหนดการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) ฟังก์ชัน

เปรียบเทียบประเภทสุ่มกับ nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T | [Object](../../system/object/) type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | T | ค่า LHS. |
| s | std::nullptr_t | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการกำหนดการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) ฟังก์ชัน

เปรียบเทียบประเภทสุ่มกับ nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T | [Object](../../system/object/) type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| rhs | std::nullptr_t | ค่า RHS. |
| s | T | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการกำหนดการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) ฟังก์ชัน

เปรียบเทียบประเภทพอยน์เตอร์.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T1& | ค่า LHS. |
| rhs | const T2& | ค่า RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการกำหนดการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1&, const T2&, long long) ฟังก์ชัน

เปรียบเทียบประเภทพอยน์เตอร์.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T1& | ค่า LHS. |
| rhs | const T2& | ค่า RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการกำหนดการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable<T2>&, long long) ฟังก์ชัน

เปรียบเทียบประเภทสุ่มกับค่าของ [Nullable](../../system/nullable/).

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | T1 | ค่า LHS. |
| rhs | const [Nullable](../../system/nullable/)<T2>& | ค่า RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการกำหนดการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable<T1>&, T2, long long) ฟังก์ชัน

เปรียบเทียบค่าของ [Nullable](../../system/nullable/) กับประเภทสุ่ม.

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const [Nullable](../../system/nullable/)<T1>& | ค่า LHS. |
| rhs | T2 | ค่า RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการกำหนดการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) ฟังก์ชัน

เปรียบเทียบประเภทสุ่มโดยใช้อัลกอริทึมของ gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | T1 | ค่า LHS. |
| rhs | T2 | ค่า RHS. |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T&, const T&, long long) ฟังก์ชัน

เปรียบเทียบสองค่า [System::String](../../system/string/) โดยป้องกันไม่ให้เรียกฟังก์ชันสมาชิกบน [String](../../system/string/) ที่เป็น null. แม่แบบ (แทนการอัปโหลดแบบธรรมดาที่รับ const [String](../../system/string/)&) เพื่อให้การเรียกแบบผสมประเภท—เช่นสตริงลิเทรัล char16_t ที่เปรียบเทียบกับ [String](../../system/string/)—ไม่สามารถสรุป T ที่สอดคล้องและจึงไม่ถูกพิจารณาเป็นตัวเลือกนี้, แทนที่จะแข่งขันกับเทมเพลต AreEqualImpl<T1,T2> ผ่านพารามิเตอร์ตัวเลือก long long/int และทำให้เกิดการแก้ไขโอเวอร์โหลดที่คลุมเครือ.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | รายละเอียด |
| --- | --- |
| T | [Object](../../system/object/) type, constrained to [System::String](../../system/string/). |

### อาร์กิวเมนต์

| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T& | ค่า LHS. |
| rhs | const T& | ค่า RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการกำหนดการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์นี้จะถูกละเลย |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบรูปแบบ gtest.

## ดูเพิ่มเติม

* การกำหนดประเภท [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* การกำหนดประเภท [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* การกำหนดประเภท [SharedPtr](../../system/sharedptr/)
* คลาส [String](../../system/string/)
* คลาส [Object](../../system/object/)
* คลาส [Stream](../../system.io/stream/)
* คลาส [Nullable](../../system/nullable/)
* โครงสร้าง [IsSmartPtr](../../system/issmartptr/)
* โครงสร้าง [IsBoxable](../../system/isboxable/)
* โครงสร้าง [IsStringByteSequence](../../system/isstringbytesequence/)
* โครงสร้าง [IsNullable](../../system/isnullable/)
* เนมสเปซ [System::TestPredicates](../)
* ไลบรารี [Aspose.Slides](../../)