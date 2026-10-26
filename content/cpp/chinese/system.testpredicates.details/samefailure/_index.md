---
title: SameFailure()
second_title: Aspose.Slides C++ API 参考
description: 为输出格式化 'same' 断言失败。
type: docs
weight: 53
url: /zh/system.testpredicates.details/samefailure/
---
## System::TestPredicates::Details::SameFailure(const char *, const char *, T1\&, T2\&) 函数

为输出格式化 'same' 断言失败。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | LHS 值类型。 |
| T2 | RHS 值类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | LHS 表达式。 |
| rhs_expr | const char * | RHS 表达式。 |
| lhs | T1\& | LHS 值。 |
| rhs | T2\& | RHS 值。 |

### 返回值

[Object](../../system/object/) 包装失败文本。

## 另请参见

* 命名空间 [System::TestPredicates::Details](../)
* 库 [Aspose.Slides](../../)