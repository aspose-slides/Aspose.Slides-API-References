---
title: AreEqual()
second_title: Aspose.Slides C++ API 参考
description: 对 AreEqual 断言的参数进行相等比较。
type: docs
weight: 14
url: /zh/system.testpredicates/areequal/
---
## System::TestPredicates::AreEqual(const char *, const char *, T1\&&, T2\&&) function

对 AreEqual 断言的参数进行相等比较。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
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
| lhs | T1\&& | 左侧值。 |
| rhs | T2\&& | 右侧值。 |

### 返回值

gtest 样式的断言结果。

## 另见

* 命名空间 [System::TestPredicates](../)
* 库 [Aspose.Slides](../../)