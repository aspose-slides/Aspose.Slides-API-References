---
title: AreEqualImpl()
second_title: Aspose.Slides สำหรับอ้างอิง API C++
description: เปรียบเทียบความเท่ากันระหว่างค่าจุดลอยกับประเภทเชิงคณิตศาสตร์
type: docs
weight: 27
url: /th/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) ฟังก์ชัน

เปรียบเทียบเท่ากันระหว่างค่าจุดลอยกับประเภทเชิงคณิตศาสตร์

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทออบเจ็กต์ LHS. |
| T2 | ประเภทออบเจ็กต์ RHS. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T1 | ค่าของ LHS. |
| rhs | const T2 | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) ฟังก์ชัน

เปรียบเทียบเท่ากันระหว่างค่าที่หนึ่งหรือทั้งสองเป็น [Decimal](../../system/decimal/)

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทออบเจ็กต์ LHS. |
| T2 | ประเภทออบเจ็กต์ RHS. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T1\& | ค่าของ LHS. |
| rhs | const T2\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) ฟังก์ชัน

เปรียบเทียบเท่ากันระหว่างประเภทที่ไม่ใช่พอยน์เตอร์โดยใช้เมธอด Equals ที่ให้มา

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภท [Object](../../system/object/). |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T\& | ค่าของ LHS. |
| rhs | const T\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) ฟังก์ชัน

เปรียบเทียบเท่ากันระหว่างประเภทที่ไม่ใช่พอยน์เตอร์โดยใช้เมธอด Equals ที่ให้มา

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภท [Object](../../system/object/). |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | T\& | ค่าของ LHS. |
| rhs | const T\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) ฟังก์ชัน

เปรียบเทียบเท่ากันระหว่างประเภทที่ไม่ใช่พอยน์เตอร์โดยใช้ตัวดำเนินการ == ที่ให้มา

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภท [Object](../../system/object/). |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T\& | ค่าของ LHS. |
| rhs | const T\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) ฟังก์ชัน

เปรียบเทียบเท่ากันระหว่างประเภทที่สามารถบรรจุได้กับค่า [SmartPtr](../../system/smartptr/)

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภท [Object](../../system/object/). |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | T | ค่าของ LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) ฟังก์ชัน

เปรียบเทียบเท่ากันระหว่างประเภทที่สามารถบรรจุได้กับค่า [SmartPtr](../../system/smartptr/)

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภท [Object](../../system/object/). |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | ค่าของ LHS. |
| rhs | T | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) ฟังก์ชัน

เปรียบเทียบเท่ากันระหว่างสตริงลิเทรัลกับค่า [SmartPtr](../../system/smartptr/) โดยใช้การแยกบรรจุ

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const char16_t * | ค่าของ LHS. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) ฟังก์ชัน

เปรียบเทียบเท่ากันระหว่างสตริงลิเทรัลกับค่า [SmartPtr](../../system/smartptr/) โดยใช้การแยกบรรจุ

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | ค่าของ LHS. |
| rhs | const char16_t * | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) ฟังก์ชัน

เปรียบเทียบเท่ากันระหว่างประเภทสุ่มกับ nullptr

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภท [Object](../../system/object/). |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | T | ค่าของ LHS. |
| s | std::nullptr_t | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) ฟังก์ชัน

เปรียบเทียบเท่ากันระหว่างประเภทสุ่มกับ nullptr

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภท [Object](../../system/object/). |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| rhs | std::nullptr_t | ค่าของ RHS. |
| s | T | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) ฟังก์ชัน

เปรียบเทียบเท่ากันระหว่างประเภทพอยน์เตอร์

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภท LHS. |
| T2 | ประเภท RHS. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T1\& | ค่าของ LHS. |
| rhs | const T2\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) ฟังก์ชัน

เปรียบเทียบเท่ากันระหว่างประเภทพอยน์เตอร์

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภท LHS. |
| T2 | ประเภท RHS. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const T1\& | ค่าของ LHS. |
| rhs | const T2\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) ฟังก์ชัน

เปรียบเทียบเท่ากันระหว่างประเภทสุ่มกับค่า [Nullable](../../system/nullable/)

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภท LHS. |
| T2 | ประเภท RHS. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | T1 | ค่าของ LHS. |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) ฟังก์ชัน

เปรียบเทียบเท่ากันระหว่างค่า [Nullable](../../system/nullable/) กับประเภทสุ่ม

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภท LHS. |
| T2 | ประเภท RHS. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | ค่าของ LHS. |
| rhs | T2 | ค่าของ RHS. |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เป็นตัวเลือกของการทำงานของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเว้น |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) ฟังก์ชัน

เปรียบเทียบเท่ากันระหว่างประเภทสุ่มโดยใช้อัลกอริทึมของ gtest

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภท LHS. |
| T2 | ประเภท RHS. |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ LHS. |
| rhs_expr | const char * | นิพจน์ RHS. |
| lhs | T1 | ค่าของ LHS. |
| rhs | T2 | ค่าของ RHS. |

### ค่าที่ส่งคืน

ผลลัพธ์การตรวจสอบแบบ gtest

## ดูเพิ่มเติม

* Typedef [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* คลาส [Object](../../system/object/)
* คลาส [Stream](../../system.io/stream/)
* คลาส [Nullable](../../system/nullable/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Struct [IsStringByteSequence](../../system/isstringbytesequence/)
* Struct [IsNullable](../../system/isnullable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)