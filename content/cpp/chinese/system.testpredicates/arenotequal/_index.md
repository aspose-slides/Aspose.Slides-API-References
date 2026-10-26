---
title: AreNotEqual()
second_title: Aspose.Slides for C++ API 参考
description: 不等比较用于 AreEqual 断言的参数翻译。
type: docs
weight: 40
url: /zh/system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) 函数

不等比较用于 AreEqual 断言的参数翻译。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | LHS 对象类型。 |
| T2 | RHS 对象类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 表达式。 |
| rhs_expr | const char * | RHS 表达式。 |
| lhs | T1\&& | LHS 值。 |
| rhs | T2\&& | RHS 值。 |

### 返回值

gtest-styled 断言结果。

## 另请参见

* 命名空间 [System::TestPredicates](../)
* 库 [Aspose.Slides](../../)