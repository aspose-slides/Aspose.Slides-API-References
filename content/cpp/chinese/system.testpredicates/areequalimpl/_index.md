---
title: AreEqualImpl()
second_title: Aspose.Slides for C++ API 参考
description: 对浮点数和算术类型进行相等比较。
type: docs
weight: 27
url: /zh/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) 函数

对浮点数和算术类型进行相等比较。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AreFPandArithmetic<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 lhs, const T2 rhs, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 左侧对象类型。 |
| T2 | 右侧对象类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | const T1 | 左侧值。 |
| rhs | const T2 | 右侧值。 |
| s | long long | 一个服务参数，用作函数实现的选择器；该参数的值被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 函数

对值进行相等比较，其中一个或两个是 [Decimal](../../system/decimal/)。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 左侧对象类型。 |
| T2 | 右侧对象类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | const T1\& | 左侧值。 |
| rhs | const T2\& | 右侧值。 |
| s | long long | 一个服务参数，用作函数实现的选择器；该参数的值被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) 函数

使用提供的 Equals 方法对非指针类型进行相等比较。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | const T\& | 左侧值。 |
| rhs | const T\& | 右侧值。 |
| s | long long | 一个服务参数，用作函数实现的选择器；该参数的值被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) 函数

使用提供的 Equals 方法对非指针类型进行相等比较。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | T\& | 左侧值。 |
| rhs | const T\& | 右侧值。 |
| s | long long | 一个服务参数，用作函数实现的选择器；该参数的值被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) 函数

使用提供的 == 运算符对非指针类型进行相等比较。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | const T\& | 左侧值。 |
| rhs | const T\& | 右侧值。 |
| s | long long | 一个服务参数，用作函数实现的选择器；该参数的值被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) 函数

对可装箱类型与 [SmartPtr](../../system/smartptr/) 值进行相等比较。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | T | 左侧值。 |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | 右侧值。 |
| s | long long | 一个服务参数，用作函数实现的选择器；该参数的值被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) 函数

对可装箱类型与 [SmartPtr](../../system/smartptr/) 值进行相等比较。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value &&!IsStringByteSequence<T, char16_t>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | 左侧值。 |
| rhs | T | 右侧值。 |
| s | long long | 一个服务参数，用作函数实现的选择器；该参数的值被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) 函数

使用拆箱，将字符串字面量与 [SmartPtr](../../system/smartptr/) 值进行相等比较。

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const char16_t *lhs, const System::SharedPtr<Object> &rhs, long long s)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | const char16_t * | 左侧值。 |
| rhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | 右侧值。 |
| s | long long | 一个服务参数，用作函数实现的选择器；该参数的值被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) 函数

使用拆箱，将字符串字面量与 [SmartPtr](../../system/smartptr/) 值进行相等比较。

```cpp
testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, const char16_t *rhs, long long s)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | const [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\& | 左侧值。 |
| rhs | const char16_t * | 右侧值。 |
| s | long long | 一个服务参数，用作函数实现的选择器；该参数的值被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) 函数

对随机类型与 nullptr 进行相等比较。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | T | 左侧值。 |
| s | std::nullptr_t | 一个服务参数，用作函数实现的选择器；该参数的值被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) 函数

对随机类型与 nullptr 进行相等比较。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| rhs | std::nullptr_t | 右侧值。 |
| s | T | 一个服务参数，用作函数实现的选择器；该参数的值被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 函数

对指针类型进行相等比较。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&(!std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value||!std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 左侧类型。 |
| T2 | 右侧类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | const T1\& | 左侧值。 |
| rhs | const T2\& | 右侧值。 |
| s | long long | 一个服务参数，用作函数实现的选择器；该参数的值被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 函数

对指针类型进行相等比较。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value &&std::is_base_of<System::IO::Stream, typenameT1::Pointee_>::value &&std::is_base_of<System::IO::Stream, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 左侧类型。 |
| T2 | 右侧类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | const T1\& | 左侧值。 |
| rhs | const T2\& | 右侧值。 |
| s | long long | 一个服务参数，用作函数实现的选择器；该参数的值被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) 函数

对随机类型与 [Nullable](../../system/nullable/) 值进行相等比较。

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T1>::value &&!IsNullable<T1>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, const Nullable<T2> &rhs, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 左侧类型。 |
| T2 | 右侧类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | T1 | 左侧值。 |
| rhs | const [Nullable](../../system/nullable/)\<T2\>\& | 右侧值。 |
| s | long long | 一个服务参数，用作函数实现的选择器；该参数的值被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) 函数

对 [Nullable](../../system/nullable/) 值与随机类型进行相等比较。

```cpp
template<typename T1,typename T2> std::enable_if<!std::is_null_pointer<T2>::value &&!IsNullable<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const Nullable<T1> &lhs, T2 rhs, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 左侧类型。 |
| T2 | 右侧类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | const [Nullable](../../system/nullable/)\<T1\>\& | 左侧值。 |
| rhs | T2 | 右侧值。 |
| s | long long | 一个服务参数，用作函数实现的选择器；该参数的值被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) 函数

使用 gtest 算法对随机类型进行相等比较。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 左侧类型。 |
| T2 | 右侧类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | T1 | 左侧值。 |
| rhs | T2 | 右侧值。 |

### 返回值

gtest 风格的断言结果。

## 另见

* 类型定义 [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* 类型定义 [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* 类型定义 [SharedPtr](../../system/sharedptr/)
* 类 [Object](../../system/object/)
* 类 [Stream](../../system.io/stream/)
* 类 [Nullable](../../system/nullable/)
* 结构体 [IsSmartPtr](../../system/issmartptr/)
* 结构体 [IsBoxable](../../system/isboxable/)
* 结构体 [IsStringByteSequence](../../system/isstringbytesequence/)
* 结构体 [IsNullable](../../system/isnullable/)
* 命名空间 [System::TestPredicates](../)
* 库 [Aspose.Slides](../../)