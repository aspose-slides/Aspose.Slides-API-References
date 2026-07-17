---
title: NotEqFailure()
second_title: Aspose.Slides C++ API 参考
description: 格式化 != 断言失败的输出。
type: docs
weight: 40
url: /zh/system.testpredicates.details/noteqfailure/
---
## System::TestPredicates::Details::NotEqFailure(const char *, const char *, T1\&, T2\&) 函数

格式化 != 断言失败的输出。

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotEqFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T1 | LHS value type. |
| T2 | RHS value type. |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1\& | LHS value. |
| rhs | T2\& | RHS value. |

### 返回值

[Object](../../system/object/) 包装失败文本。

## 另见

* 命名空间 [System::TestPredicates::Details](../)
* 库 [Aspose.Slides](../../)