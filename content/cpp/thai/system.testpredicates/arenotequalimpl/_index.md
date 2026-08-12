---
title: AreNotEqualImpl()
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: การเปรียบเทียบแบบไม่เท่ากันจะเปรียบเทียบค่าที่หนึ่งหรือทั้งสองค่าเป็น Decimal.
type: docs
weight: 53
url: /th/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) ฟังก์ชัน

การเปรียบเทียบแบบไม่เท่ากัน (Not-equal) จะเปรียบเทียบค่าหนึ่งหรือทั้งสองค่าเป็น [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทวัตถุด้านซ้าย |
| T2 | ประเภทวัตถุด้านขวา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ด้านซ้าย |
| rhs_expr | const char * | นิพจน์ด้านขวา |
| lhs | const T1\& | ค่าด้านซ้าย |
| rhs | const T2\& | ค่าด้านขวา |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เลือกการดำเนินการของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเลย |

### ค่าที่ส่งกลับ

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) ฟังก์ชัน

การเปรียบเทียบไม่เท่ากันสำหรับประเภทที่ไม่ใช่ตัวชี้โดยใช้เมธอด Equals ที่ให้มา.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภท [Object](../../system/object/) |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ด้านซ้าย |
| rhs_expr | const char * | นิพจน์ด้านขวา |
| lhs | const T\& | ค่าด้านซ้าย |
| rhs | const T\& | ค่าด้านขวา |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เลือกการดำเนินการของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเลย |

### ค่าที่ส่งกลับ

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) ฟังก์ชัน

การเปรียบเทียบไม่เท่ากันสำหรับประเภทที่ไม่ใช่ตัวชี้โดยใช้เมธอด Equals ที่ให้มา.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภท [Object](../../system/object/) |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ด้านซ้าย |
| rhs_expr | const char * | นิพจน์ด้านขวา |
| lhs | T\& | ค่าด้านซ้าย |
| rhs | const T\& | ค่าด้านขวา |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เลือกการดำเนินการของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเลย |

### ค่าที่ส่งกลับ

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) ฟังก์ชัน

การเปรียบเทียบไม่เท่ากันสำหรับประเภทที่ไม่ใช่ตัวชี้โดยใช้ตัวดำเนินการ != ที่ให้มา.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภท [Object](../../system/object/) |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ด้านซ้าย |
| rhs_expr | const char * | นิพจน์ด้านขวา |
| lhs | const T\& | ค่าด้านซ้าย |
| rhs | const T\& | ค่าด้านขวา |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เลือกการดำเนินการของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเลย |

### ค่าที่ส่งกลับ

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) ฟังก์ชัน

การเปรียบเทียบไม่เท่ากันสำหรับค่าที่สามารถบรรจุได้ด้วย [SmartPtr](../../system/smartptr/) โดยทำการ unboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภท [Object](../../system/object/) |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ด้านซ้าย |
| rhs_expr | const char * | นิพจน์ด้านขวา |
| lhs | T | ค่าด้านซ้าย |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | ค่าด้านขวา |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เลือกการดำเนินการของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเลย |

### ค่าที่ส่งกลับ

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) ฟังก์ชัน

การเปรียบเทียบไม่เท่ากันสำหรับค่าที่สามารถบรรจุได้ด้วย [SmartPtr](../../system/smartptr/) โดยทำการ unboxing.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภท [Object](../../system/object/) |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ด้านซ้าย |
| rhs_expr | const char * | นิพจน์ด้านขวา |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | ค่าด้านซ้าย |
| rhs | T | ค่าด้านขวา |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เลือกการดำเนินการของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเลย |

### ค่าที่ส่งกลับ

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) ฟังก์ชัน

การเปรียบเทียบไม่เท่ากันสำหรับประเภทสุ่มกับ nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภท [Object](../../system/object/) |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ด้านซ้าย |
| rhs_expr | const char * | นิพจน์ด้านขวา |
| lhs | T | ค่าด้านซ้าย |
| s | std::nullptr_t | พารามิเตอร์บริการที่ทำหน้าที่เลือกการดำเนินการของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเลย |

### ค่าที่ส่งกลับ

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) ฟังก์ชัน

การเปรียบเทียบไม่เท่ากันสำหรับประเภทสุ่มกับ nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T | ประเภท [Object](../../system/object/) |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ด้านซ้าย |
| rhs_expr | const char * | นิพจน์ด้านขวา |
| rhs | std::nullptr_t | ค่าด้านขวา |
| s | T | พารามิเตอร์บริการที่ทำหน้าที่เลือกการดำเนินการของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเลย |

### ค่าที่ส่งกลับ

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) ฟังก์ชัน

การเปรียบเทียบเท่ากับสำหรับประเภทตัวชี้.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทด้านซ้าย |
| T2 | ประเภทด้านขวา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ด้านซ้าย |
| rhs_expr | const char * | นิพจน์ด้านขวา |
| lhs | const T1\& | ค่าด้านซ้าย |
| rhs | const T2\& | ค่าด้านขวา |
| s | long long | พารามิเตอร์บริการที่ทำหน้าที่เลือกการดำเนินการของฟังก์ชัน; ค่าของพารามิเตอร์จะถูกละเลย |

### ค่าที่ส่งกลับ

ผลลัพธ์การตรวจสอบแบบ gtest

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) ฟังก์ชัน

การเปรียบเทียบเท่ากับสำหรับประเภทสุ่มโดยใช้ gtest altorithms.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### พารามิเตอร์แม่แบบ

| พารามิเตอร์ | คำอธิบาย |
| --- | --- |
| T1 | ประเภทด้านซ้าย |
| T2 | ประเภทด้านขวา |

### อาร์กิวเมนต์

| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| lhs_expr | const char * | นิพจน์ด้านซ้าย |
| rhs_expr | const char * | นิพจน์ด้านขวา |
| lhs | T1 | ค่าด้านซ้าย |
| rhs | T2 | ค่าด้านขวา |

### ค่าที่ส่งกลับ

ผลลัพธ์การตรวจสอบแบบ gtest

## ดูเพิ่มเติม

* Typedef [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Object](../../system/object/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Struct [IsBoxable](../../system/isboxable/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)