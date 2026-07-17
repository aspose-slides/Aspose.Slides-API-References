---
title: AreNotEqual()
second_title: Aspose.Slides C++ API 参考
description: 对 AreNotEqual 断言的参数进行不等比较。
type: docs
weight: 131
url: /zh/system.testpredicates.details.sharedptrasserts/arenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *, const char *, const T1\&, const T2\&) function

对 AreNotEqual 断言的参数进行不等比较。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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

gtest 样式的断言结果。

## 另请参见

* 命名空间 [System::TestPredicates::Details::SharedPtrAsserts](../)
* 库 [Aspose.Slides](../../)