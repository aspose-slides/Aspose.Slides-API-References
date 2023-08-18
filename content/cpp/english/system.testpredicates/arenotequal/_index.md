---
title: AreNotEqual()
second_title: Aspose.Slides for C++ API Reference
description: Not-equal-compares arguments for AreEqual assertion translation.
type: docs
weight: 40
url: /system.testpredicates/arenotequal/
---
## System::TestPredicates::AreNotEqual(const char *, const char *, T1\&&, T2\&&) function


Not-equal-compares arguments for AreEqual assertion translation.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotEqual(const char *lhs_expr, const char *rhs_expr, T1 &&lhs, T2 &&rhs)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | LHS object type. |
| T2 | RHS object type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| lhs | T1\&& | LHS value. |
| rhs | T2\&& | RHS value. |

### Return Value

gtest-styled assertion result.

## See Also

* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)