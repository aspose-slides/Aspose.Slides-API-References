---
title: AreEqualImpl()
second_title: Aspose.Slides for C++ API 参考
description: 对浮点数与算术类型进行相等比较。
type: docs
weight: 27
url: /zh/system.testpredicates/areequalimpl/
---
## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1, const T2, long long) function

对浮点数与算术类型进行相等比较。

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
| s | long long | 作为函数实现选择器的服务参数；该参数的值将被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

比较值，其中一个或两个为 [Decimal](../../system/decimal/)。

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
| s | long long | 作为函数实现选择器的服务参数；该参数的值将被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

使用提供的 Equals 方法比较非指针类型。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
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
| s | long long | 作为函数实现选择器的服务参数；该参数的值将被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T\&, const T\&, long long) function

使用提供的 Equals 方法比较非指针类型。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
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
| s | long long | 作为函数实现选择器的服务参数；该参数的值将被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

使用提供的 operator == 比较非指针类型。

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
| s | long long | 作为函数实现选择器的服务参数；该参数的值将被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) function

比较可装箱类型与 [SmartPtr](../../system/smartptr/) 值。

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
| s | long long | 作为函数实现选择器的服务参数；该参数的值将被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) function

比较可装箱类型与 [SmartPtr](../../system/smartptr/) 值。

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
| s | long long | 作为函数实现选择器的服务参数；该参数的值将被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const char16_t *, const System::SharedPtr\<Object\>\&, long long) function

使用拆箱将字符串字面量与 [SmartPtr](../../system/smartptr/) 值进行比较。

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
| s | long long | 作为函数实现选择器的服务参数；该参数的值将被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, const char16_t *, long long) function

使用拆箱将字符串字面量与 [SmartPtr](../../system/smartptr/) 值进行比较。

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
| s | long long | 作为函数实现选择器的服务参数；该参数的值将被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T, std::nullptr_t, long long) function

比较随机类型与 nullptr。

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
| s | std::nullptr_t | 作为函数实现选择器的服务参数；该参数的值将被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, std::nullptr_t, T, long long) function

比较随机类型与 nullptr。

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
| s | T | 作为函数实现选择器的服务参数；该参数的值将被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

比较指针类型是否相等。

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
| s | long long | 作为函数实现选择器的服务参数；该参数的值将被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) function

比较指针类型是否相等。

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
| s | long long | 作为函数实现选择器的服务参数；该参数的值将被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, const Nullable\<T2\>\&, long long) function

比较随机类型与 [Nullable](../../system/nullable/) 值。

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
| s | long long | 作为函数实现选择器的服务参数；该参数的值将被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, const Nullable\<T1\>\&, T2, long long) function

比较 [Nullable](../../system/nullable/) 值与随机类型。

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
| s | long long | 作为函数实现选择器的服务参数；该参数的值将被忽略。 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreEqualImpl(const char *, const char *, T1, T2, int) function

使用 gtest 算法比较随机类型。

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

## System::TestPredicates::AreEqualImpl(const char *, const char *, const T\&, const T\&, long long) function

比较两个 [System::String](../../system/string/) 值，防止在空的 [String](../../system/string/) 上调用成员函数。使用模板（而非接受 const [String](../../system/string/)& 的普通重载），使得混合类型调用——例如将 char16_t 字符串字面量与 [String](../../system/string/) 进行比较——无法推断出单一一致的 T，从而完全排除该候选，而不是通过 long long/int 选择器参数与通用的 AreEqualImpl<T1,T2> 模板竞争，导致二义性重载解析。

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 类型，受限于 [System::String](../../system/string/)。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | 左侧表达式。 |
| rhs_expr | const char * | 右侧表达式。 |
| lhs | const T\& | 左侧值。 |
| rhs | const T\& | 右侧值。 |
| s | long long | 作为函数实现选择器的服务参数；该参数的值将被忽略。 |

### 返回值

gtest 风格的断言结果。

## 另请参见

* 类型别名 [AreFPandArithmetic](../../system.testpredicates.typetraits/arefpandarithmetic/)
* 类型别名 [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* 类型别名 [SharedPtr](../../system/sharedptr/)
* 类 [String](../../system/string/)
* 类 [Object](../../system/object/)
* 类 [Stream](../../system.io/stream/)
* 类 [Nullable](../../system/nullable/)
* 结构体 [IsSmartPtr](../../system/issmartptr/)
* 结构体 [IsBoxable](../../system/isboxable/)
* 结构体 [IsStringByteSequence](../../system/isstringbytesequence/)
* 结构体 [IsNullable](../../system/isnullable/)
* 命名空间 [System::TestPredicates](../)
* 库 [Aspose.Slides](../../)