---
title: AreNotEqualImpl()
second_title: Aspose.Slides for C++ API 参考
description: 对值进行不等比较，其中一个或两个为 Decimal。
type: docs
weight: 53
url: /zh/system.testpredicates/arenotequalimpl/
---
## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 函数

对值进行不相等比较，其中一个或两个为 [Decimal](../../system/decimal/)。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::AnyOfDecimal<T1, T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | 用于选择函数实现的服务参数；该参数的值被忽略 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) 函数

对两个 [System::String](../../system/string/) 值进行不相等比较，以防在空的 [String](../../system/string/) 上调用成员函数。模板化以提供与上述 AreEqualImpl [String](../../system/string/) 重载相同的基于推导的排除原因。

```cpp
template<typename T> std::enable_if<std::is_same<T, System::String>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
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
| s | long long | 用于选择函数实现的服务参数；该参数的值被忽略 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) 函数

对非指针类型使用提供的 Equals 方法进行不相等比较。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
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
| s | long long | 用于选择函数实现的服务参数；该参数的值被忽略 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T\&, const T\&, long long) 函数

对非指针类型使用提供的 Equals 方法进行不相等比较。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&!std::is_same<T, System::String>::value &&detail::has_method_equals<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T &lhs, const T &rhs, long long s)
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
| s | long long | 用于选择函数实现的服务参数；该参数的值被忽略 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T\&, const T\&, long long) 函数

对非指针类型使用提供的 != 运算符进行不相等比较。

```cpp
template<typename T> std::enable_if<!IsSmartPtr<T>::value &&std::is_class<T>::value &&!detail::has_method_equals<T>::value &&detail::has_operator_equal<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T &lhs, const T &rhs, long long s)
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
| s | long long | 用于选择函数实现的服务参数；该参数的值被忽略 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, const System::SharedPtr\<Object\>\&, long long) 函数

对可装箱的 [SmartPtr](../../system/smartptr/) 值使用拆箱进行不相等比较。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, const System::SharedPtr<Object> &rhs, long long s)
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
| s | long long | 用于选择函数实现的服务参数；该参数的值被忽略 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const System::SharedPtr\<Object\>\&, T, long long) 函数

对可装箱的 [SmartPtr](../../system/smartptr/) 值使用拆箱进行不相等比较。

```cpp
template<typename T> std::enable_if<IsBoxable<T>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const System::SharedPtr<Object> &lhs, T rhs, long long s)
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
| s | long long | 用于选择函数实现的服务参数；该参数的值被忽略 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T, std::nullptr_t, long long) 函数

对随机类型与 nullptr 进行不相等比较。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T lhs, std::nullptr_t, long long s)
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
| s | std::nullptr_t | 用于选择函数实现的服务参数；该参数的值被忽略 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, std::nullptr_t, T, long long) 函数

对随机类型与 nullptr 进行不相等比较。

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, std::nullptr_t, T rhs, long long s)
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
| s | T | 用于选择函数实现的服务参数；该参数的值被忽略 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 函数

等于比较指针类型。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| s | long long | 用于选择函数实现的服务参数；该参数的值被忽略 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreNotEqualImpl(const char *, const char *, T1, T2, int) 函数

等于比较随机类型，使用 gtest 算法。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqualImpl(const char *lhs_expr, const char *rhs_expr, T1 lhs, T2 rhs, int)
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

* 类型别名 [AnyOfDecimal](../../system.testpredicates.typetraits/anyofdecimal/)
* 类型别名 [SharedPtr](../../system/sharedptr/)
* 类 [String](../../system/string/)
* 类 [Object](../../system/object/)
* 结构体 [IsSmartPtr](../../system/issmartptr/)
* 结构体 [IsBoxable](../../system/isboxable/)
* 命名空间 [System::TestPredicates](../)
* 库 [Aspose.Slides](../../)