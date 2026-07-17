---
title: NotNullAreEqualImpl()
second_title: Aspose.Slides for C++ API 参考
description: 对数组或列表进行相等比较。
type: docs
weight: 40
url: /zh/system.testpredicates.details.sharedptrasserts/notnullareequalimpl/
---
## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 函数


对数组或列表进行相等比较。

```cpp
template<typename T1,typename T2> std::enable_if<TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value, testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 左侧容器类型。 |
| T2 | 右侧容器类型。 |

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

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, long long) 函数


对 IEnumerable 实例进行相等比较。

```cpp
template<typename T1,typename T2> std::enable_if<!TypeTraits::BothArrayOrList<typenameT1::Pointee_, typenameT2::Pointee_>::value &&TypeTraits::BothEnumerable<typenameT1::Pointee_, typenameT2::Pointee_>::value &&(!TypeTraits::has_data_method<typenameT1::Pointee_>::value||!TypeTraits::has_data_method<typenameT2::Pointee_>::value), testing::AssertionResult>::type System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | 左侧元素类型。 |
| T2 | 右侧元素类型。 |

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

## System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *, const char *, const T1\&, const T2\&, int32_t) 函数


使用 Equals 方法对未知类型进行相等比较。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::NotNullAreEqualImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int32_t)
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

### 返回值

gtest 风格的断言结果。

## 另见

* 类型定义 [BothArrayOrList](../../system.testpredicates.typetraits/botharrayorlist/)
* 类型定义 [BothEnumerable](../../system.testpredicates.typetraits/bothenumerable/)
* 结构体 [has_data_method](../../system.testpredicates.typetraits/has_data_method/)
* 命名空间 [System::TestPredicates::Details::SharedPtrAsserts](../)
* 库 [Aspose.Slides](../../)