---
title: IsInstanceOf()
second_title: Aspose.Slides for C++ API Reference
description: Is-instance-of-compares arguments for IsInstanceOf assertion translation.
type: docs
weight: 118
url: /cpp/system.testpredicates/isinstanceof/
---
## System::TestPredicates::IsInstanceOf(const char *, const char *, const [TypeInfo](../../system/typeinfo/)\&, const T\&) function


Is-instance-of-compares arguments for IsInstanceOf assertion translation.

```cpp
template<typename T> testing::AssertionResult System::TestPredicates::IsInstanceOf(const char *lhs_expr, const char *rhs_expr, const TypeInfo &typeInfo, const T &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Argument type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhs_expr | const char * | LHS expression. |
| rhs_expr | const char * | RHS expression. |
| typeInfo | const [TypeInfo](../../system/typeinfo/)\& | A typeInfo object that represents a type against which the type of **obj** is to be compared |
| obj | const T\& | An object whose type to compare with the specified type |

### Return Value

gtest-styled assertion result.

## See Also

* Class [TypeInfo](../../system/typeinfo/)
* Namespace [System::TestPredicates](../)
* Library [Aspose.Slides](../../)
