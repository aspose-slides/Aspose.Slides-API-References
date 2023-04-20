---
title: AreNotSame()
second_title: Aspose.Slides for C++ API Reference
description: Are-not-same-compares arguments for AreSame assertion translation.
type: docs
weight: 1
url: /cpp/system.testpredicates/arenotsame/
---
## System::TestPredicates::AreNotSame(const char *, const char *, const T1\&, const T2\&) function


Are-not-same-compares arguments for AreSame assertion translation.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::AreNotSame(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
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
| lhs | const T1\& | LHS value. |
| rhs | const T2\& | RHS value. |

### Return Value

gtest-styled assertion result.

## See Also

* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)