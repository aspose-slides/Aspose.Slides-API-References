---
title: NotSameFailure()
second_title: Aspose.Slides for C++ API Reference
description: Formats 'not same' assertion failure for output.
type: docs
weight: 66
url: /cpp/system.testpredicates.details/notsamefailure/
---
## System::TestPredicates::Details::NotSameFailure(const char *, const char *, T1\&, T2\&) function


Formats 'not same' assertion failure for output.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::NotSameFailure(const char *lhs_expr, const char *rhs_expr, T1 &lhs, T2 &rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | LHS value type. |
| T2 | RHS value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1\& | LHS value. |
| rhs | T2\& | RHS value. |

### Return Value

[Object](../../system/object/) wrapping failure text.

## See Also

* Namespace [System::TestPredicates::Details](../)
* Library [Aspose.Slides](../../)
