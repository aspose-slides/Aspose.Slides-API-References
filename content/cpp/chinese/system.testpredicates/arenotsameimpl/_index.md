---
title: AreNotSameImpl()
second_title: Aspose.Slides C++ API 参考
description: Are-not-same 比较智能指针。
type: docs
weight: 105
url: /zh/system.testpredicates/arenotsameimpl/
---
## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1&, const T2&, long long) 函数


比较智能指针是否不同。

```cpp
template<typename T1,typename T2> std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, testing::AssertionResult>::type System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, long long s)
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
| lhs | const T1& | 左侧值。 |
| rhs | const T2& | 右侧值。 |
| s | long long | 用作函数实现选择器的服务参数；该参数的值会被忽略 |

### 返回值

gtest 风格的断言结果。

## System::TestPredicates::AreNotSameImpl(const char *, const char *, const T1&, const T2&, int) 函数


比较非指针值是否不同。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSameImpl(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs, int)
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
| lhs | const T1& | 左侧值。 |
| rhs | const T2& | 右侧值。 |

### 返回值

gtest 风格的断言结果。

## 另见

* 结构体 [IsSmartPtr](../../system/issmartptr/)
* 命名空间 [System::TestPredicates](../)
* 库 [Aspose.Slides](../../)