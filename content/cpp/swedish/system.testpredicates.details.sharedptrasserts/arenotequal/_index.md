---
title: AreNotEqual()
second_title: Aspose.Slides för C++ API-referens
description: Icke-lika jämför argument för AreNotEqual-påståendet.
type: docs
weight: 131
url: /sv/system.testpredicates.details.sharedptrasserts/arenotequal/
---
## System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *, const char *, const T1\&, const T2\&) function


Icke-lika jämför argument för AreNotEqual-påståendet.

```cpp
template<typename T1,typename T2> testing::AssertionResult System::TestPredicates::Details::SharedPtrAsserts::AreNotEqual(const char *lhs_expr, const char *rhs_expr, const T1 &lhs, const T2 &rhs)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | LHS objektstyp. |
| T2 | RHS objektstyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lhs_expr | const char * | LHS uttryck. |
| rhs_expr | const char * | RHS uttryck. |
| lhs | const T1\& | LHS värde. |
| rhs | const T2\& | RHS värde. |

### Returvärde

gtest-stylat påståenderesultat.

## Se även

* Namespace [System::TestPredicates::Details::SharedPtrAsserts](../)
* Library [Aspose.Slides](../../)