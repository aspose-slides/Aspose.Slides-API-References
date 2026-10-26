---
title: AreNotEqualImpl()
second_title: Tham chiếu API Aspose.Slides cho C++
description: So sánh không bằng các giá trị, một hoặc cả hai trong số chúng là Decimal.
type: docs
weight: 53
url: /vi/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) hàm


So sánh không bằng các giá trị, một hoặc cả hai trong số chúng là [Decimal](../../system/decimal/).

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Tham số mẫu

| Tham số | Mô tả |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Đối số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Giá trị trả về

kết quả khẳng định kiểu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) hàm


So sánh không bằng hai giá trị [System::String](../../system/string/), đồng thời bảo vệ việc gọi hàm thành viên trên một [String](../../system/string/) null. Được mẫu hoá vì cùng các lý do loại trừ dựa trên suy luận như phiên bản quá tải AreEqualImpl [String](../../system/string/) ở trên.

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Tham số mẫu

| Tham số | Mô tả |
| --- | --- |
| T | [Object](../../system/object/) type, constrained to [System::String](../../system/string/). |

### Đối số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Giá trị trả về

kết quả khẳng định kiểu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) hàm


So sánh không bằng các kiểu không phải con trỏ bằng phương thức Equals được cung cấp.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Tham số mẫu

| Tham số | Mô tả |
| --- | --- |
| T | [Object](../../system/object/) kiểu. |

### Đối số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Giá trị trả về

kết quả khẳng định kiểu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) hàm


So sánh không bằng các kiểu không phải con trỏ bằng phương thức Equals được cung cấp.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```


### Tham số mẫu

| Tham số | Mô tả |
| --- | --- |
| T | [Object](../../system/object/) kiểu. |

### Đối số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Giá trị trả về

kết quả khẳng định kiểu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) hàm


So sánh không bằng các kiểu không phải con trỏ bằng toán tử != được cung cấp.

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```


### Tham số mẫu

| Tham số | Mô tả |
| --- | --- |
| T | [Object](../../system/object/) kiểu. |

### Đối số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T\& | LHS value. |
| rhs | const T\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Giá trị trả về

kết quả khẳng định kiểu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) hàm


So sánh không bằng các giá trị kiểu boxable với [SmartPtr](../../system/smartptr/) bằng cách giải hộp.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```


### Tham số mẫu

| Tham số | Mô tả |
| --- | --- |
| T | [Object](../../system/object/) kiểu. |

### Đối số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Giá trị trả về

kết quả khẳng định kiểu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) hàm


So sánh không bằng các giá trị kiểu boxable với [SmartPtr](../../system/smartptr/) bằng cách giải hộp.

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```


### Tham số mẫu

| Tham số | Mô tả |
| --- | --- |
| T | [Object](../../system/object/) kiểu. |

### Đối số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | LHS value. |
| rhs | T | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Giá trị trả về

kết quả khẳng định kiểu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) hàm


So sánh không bằng một kiểu ngẫu nhiên với nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```


### Tham số mẫu

| Tham số | Mô tả |
| --- | --- |
| T | [Object](../../system/object/) kiểu. |

### Đối số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T | LHS value. |
| s | std::nullptr_t | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Giá trị trả về

kết quả khẳng định kiểu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) hàm


So sánh không bằng một kiểu ngẫu nhiên với nullptr.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```


### Tham số mẫu

| Tham số | Mô tả |
| --- | --- |
| T | [Object](../../system/object/) kiểu. |

### Đối số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| rhs | std::nullptr_t | RHS value. |
| s | T | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Giá trị trả về

kết quả khẳng định kiểu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) hàm


So sánh bằng các kiểu con trỏ.

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### Tham số mẫu

| Tham số | Mô tả |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Đối số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |
| s | long long | A service parameter that serves as a selector of the implementation of the function; the value of the parameter is ignored |

### Giá trị trả về

kết quả khẳng định kiểu gtest.

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) hàm


So sánh bằng các kiểu ngẫu nhiên bằng thuật toán gtest.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```


### Tham số mẫu

| Tham số | Mô tả |
| --- | --- |
| T1 | LHS type. |
| T2 | RHS type. |

### Đối số

| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1 | LHS value. |
| rhs | T2 | RHS value. |

### Giá trị trả về

kết quả khẳng định kiểu gtest.

## Xem thêm

* Kiểu định nghĩa [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* Kiểu định nghĩa [SharedPtr](../../system/sharedptr/)
* Lớp [String](../../system/string/)
* Lớp [Object](../../system/object/)
* Cấu trúc [IsSmartPtr](../../system/issmartptr/)
* Cấu trúc [IsBoxable](../../system/isboxable/)
* Không gian tên [System::TestPredicates](../)
* Thư viện [Aspose.Slides](../../)